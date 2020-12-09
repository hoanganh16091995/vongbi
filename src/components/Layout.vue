<template>
  <v-app id="inspire">
    <v-app-bar
      :clipped-left="$vuetify.breakpoint.lgAndUp"
      app
      color="primary"
      dark
    >
<!--      <v-app-bar-nav-icon @click.stop="drawer = !drawer" />-->

      <v-toolbar-title
        style="width: 350px"
      >
        <a href="/" class="white--text" style="text-decoration: none;">
          <v-img
            style="background: #fff;"
            width="87px"
            height="54px"
            contain
            class="white--text align-end"
            :src="require('../assets/img/layout/Logo.png')"
            >
          </v-img>
          <!-- <v-icon>mdi-truck</v-icon>&nbsp;ShipIT -->
        </a>
      </v-toolbar-title>

      <v-text-field
        flat
        solo-inverted
        hide-details
        prepend-inner-icon="mdi-magnify"
        label="Search"
        class="hidden-sm-and-down pl-10 ml-4"
      />
      <v-spacer />
      <v-btn icon>
        <v-icon>mdi-account-circle</v-icon>
      </v-btn>
      <v-btn @click="on" icon>
        <v-badge
          content="2"
          value="2"
          color="green"
          overlap
        >
          <v-icon>mdi-bell</v-icon>
        </v-badge>
      </v-btn>
      <v-btn @click="on" href="/cart" icon>
        <v-badge
          content="2"
          value="2"
          color="green"
          overlap
        >
          <v-icon>mdi-cart</v-icon>
        </v-badge>
      </v-btn>
    </v-app-bar>
      
      <v-content>
      <v-bottom-navigation
        :value="activeBtn"
        color="primary"
        horizontal
      >
        <a href="/" class="v-btn">
          <span>Home</span>
        </a>
        <v-menu open-on-hover offset-y>
          <template v-slot:activator="{ on }">
            <v-btn v-on="on">
              <span>Shop</span>
            </v-btn>
          </template>
          <v-card
            class="mx-auto"
            max-width="344"
            outlined
          >

            <v-list-item
              v-for="(item, index) in items"
              :key="index"
              @click=""
              href="/shop"
            >
              <v-list-item-title>{{ item.title }}</v-list-item-title>
            </v-list-item>

          </v-card>
        </v-menu>
        <a href="/product" class="v-btn">
          <span>Product</span>
        </a>
        <v-btn href="/blog">
          <span>Blog</span>
        </v-btn>
      </v-bottom-navigation>
    </v-content>

      <router-view/>
    <v-footer
      :padless="true"
    >
      <v-card
        style="background-color: #DDE8EF!important; border-color: #DDE8EF!important;"
        flat
        tile
        width="100%"
        class="secondary white--text text-center"
      >
        <!-- <v-card-text>
          <v-btn
            class="mx-4 white--text"
            icon
          >
            <v-icon size="24px">mdi-home</v-icon>
          </v-btn>
          <v-btn
            class="mx-4 white--text"
            icon
          >
            <v-icon size="24px">mdi-email</v-icon>
          </v-btn>
          <v-btn
            class="mx-4 white--text"
            icon
          >
            <v-icon size="24px">mdi-calendar</v-icon>
          </v-btn>
           <v-btn
            class="mx-4 white--text"
            icon
          >
            <v-icon size="24px">mdi-delete</v-icon>
          </v-btn>

        </v-card-text> -->

        <v-card-text class="white--text pt-0">
          <v-container>
            <div class="row">
              <div class="col-2 col-md-2 col-sm-3 col-xs-12 text-center">
                <v-img
                  contain
                  class="white--text align-end"
                  :src="require('../assets/img/layout/Logo.png')"
                  >
                </v-img>
              </div>
              <div class="col-5 col-md-5 col-sm-3 col-xs-12 company-footer text-left">
                <p><strong>Công ty Trách nhiệm hữu hạn GIB Việt Nam</strong></p>

                <p>- Số ĐKKD&nbsp;0104927913&nbsp;do Sở KHĐT Tp. Hà Nội&nbsp; cấp ngày 29/09/2010</p>

                <p>Địa chỉ: Số 26TT25, Khu đô thị Văn Phú, Hà Đông, Hà Nội</p>

                <p>Tel: 02463 294 853 - Mobile: &nbsp;<em>0964 678 288</em></p>

                <p>Mail: sales5@gib.vn</p>

                <p>Website: <a href="https://gib.com.vn">https://gib.com.vn</a></p>

                <p>
                  <a href="https://gib.com.vn/thuong-hieu/vong-bi-fag-br35-p1">Vòng bi fag</a> 
                  - <a href="https://gib.com.vn/thuong-hieu/vong-bi-nsk-br37-p1">Vòng bi nsk</a>&nbsp;
                  - <a href="https://gib.com.vn/thuong-hieu/vong-bi-koyo-br39-p1">Vòng bi Koyo</a>&nbsp;
                  - <a href="https://gib.com.vn/thuong-hieu/vong-bi-skf-br36-p1">Vòng bi skf</a> 
                  - <a href="https://gib.com.vn/thuong-hieu/vong-bi-ntn-br38-p1">Vòng bi ntn</a> 
                  - <a href="https://gib.com.vn/thuong-hieu/vong-bi-thk-br40-p1">Vòng bi thk</a>
                </p>

                <p>
                  <a href="https://gib.com.vn/bai-viet/cach-phan-biet-vong-bi-skf-chinh-hang-b251.html">
                  Cách phân biệt vòng bi skf chính hãng</a>&nbsp;, <a href="https://gib.com.vn/bai-viet/tin-tuc-s1-p1">Thông tin vòng bi, bạc đạn</a>
                </p>
              </div>
              <div class="col-5 col-md-5 col-sm-3 col-xs-12 text-right company-footer">
                <span><a href="#">Trang chủ</a></span> |
                <span><a href="/bai-viet/gioi-hieu-s2-p1">Giới thiệu</a></span> |
                <span><a href="/san-pham">Sản phẩm</a></span> |
                <span><a href="/bai-viet/tai-lieu-ky-thuat-s4-p1">Tài liệu kỹ thuật</a></span> |
                <span><a href="/bai-viet/tuyen-dung-s5-p1">Tuyển dụng</a></span> |
                <span><a href="/bai-viet/lien-he-s6-p1">Liên hệ</a></span>

                <div style="color: #333; font-size: 12px;">Bản quyền thuộc về MIB Việt Nam</div>
                <p>Thiết kế bởi <a href="http://bbbgroup.vn/">Sunny</a></p>
                <a href="http://online.gov.vn/CustomWebsiteDisplay.aspx?DocId=36506"></a>
              </div>
            </div>
          </v-container>
          
        </v-card-text>

        <v-divider></v-divider>
      </v-card>
    </v-footer>
  </v-app>
</template>
<script>
    export default {
        data () {
            return {
                items: [
                    { title: 'T-Shirts' },
                    { title: 'Jackets' },
                    { title: 'Shirts' },
                    { title: 'Jeans' },
                    { title: 'Shoes' },
                ],
                activeBtn: 1,
            }
        },
        methods: {
          on () {

          }
        }
    }
</script>

<style>
  .company-footer p {
    margin-bottom: 0px;
    color: #333;
    font-size: 12px;
  }

  .company-footer {
    color: #333;
  }

  .company-footer a {
    font-size: 11px;
    color: #333;
  }

  .hotline {
    background-color: #179f6d !important;
    border-color: #3ae3d6 !important;
  }
</style>
