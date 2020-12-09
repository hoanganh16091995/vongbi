<template>
  <div>
    <v-carousel hide-delimiters
      cycle
      hide-delimiter-background
      show-arrows-on-hover
    >
      <v-carousel-item
        :src="require('../assets/img/home/slide_1.jpg')"
      >
        <v-row
          class="fill-height"
          align="center"
          justify="center"
        >
          <!-- <div class="display-2 white--text pl-5 pr-5 hidden-sm-only"><strong>Upto 60% + Extra 10%</strong></div><br/> -->
        </v-row>
      </v-carousel-item>
      <v-carousel-item
        :src="require('../assets/img/home/slide_2.jpg')"
      >
        <v-row
          class="fill-height"
          align="center"
          justify="center"
        >
        </v-row>
      </v-carousel-item>
      <v-carousel-item
        :src="require('../assets/img/home/slide_3.jpg')"
      >
        <v-row
          class="fill-height"
          align="center"
          justify="center"
        >
        </v-row>
      </v-carousel-item>
      <v-carousel-item
        :src="require('../assets/img/home/slide_4.jpg')"
      >
        <v-row
          class="fill-height"
          align="center"
          justify="center"
        >
        </v-row>
      </v-carousel-item>

    </v-carousel>

    <v-container>
      <div class="row">
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-img
                    contain
                    class="white--text align-end"
                    height="200px"
                    width="300px"
                    :src="require('../assets/img/home/FAG.jpg')"
                  >
                  </v-img>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-img
                    contain
                    class="white--text align-end"
                    height="200px"
                    width="300px"
                    :src="require('../assets/img/home/SKF.jpg')"
                  >
                  </v-img>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-img
                    contain
                    class="white--text align-end"
                    height="200px"
                    width="300px"
                    :src="require('../assets/img/home/NSK.jpg')"
                  >
                  </v-img>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-img
                    contain
                    class="white--text align-end"
                    height="200px"
                    width="300px"
                    :src="require('../assets/img/home/NTN.jpg')"
                  >
                  </v-img>
                </v-hover>
              </div>
            </div>

      <div class="row">
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-img
                    contain
                    class="white--text align-end"
                    height="200px"
                    width="300px"
                    :src="require('../assets/img/home/KOYO.jpg')"
                  >
                  </v-img>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-img
                    contain
                    class="white--text align-end"
                    height="200px"
                    width="300px"
                    :src="require('../assets/img/home/THK.jpg')"
                  >
                  </v-img>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-img
                    contain
                    class="white--text align-end"
                    height="200px"
                    width="300px"
                    :src="require('../assets/img/home/IKO.jpg')"
                  >
                  </v-img>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-img
                    contain
                    class="white--text align-end"
                    height="200px"
                    width="300px"
                    :src="require('../assets/img/home/TIMKEN.jpg')"
                  >
                  </v-img>
                </v-hover>
              </div>
            </div>
    </v-container>
    <!-- <div class="pl-4 pr-4 row">
      <div
       class="col-md-6 col-sm-6 col-xs-12"
      >
        <v-card>

          <v-img
            :src="require('../assets/img/home/slider2.jpg')"
            class="white--text align-center"
            gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
            height="400px"
          >
           <h1 class="text-center font-size">Top Picks</h1>
            <div class="text-center">
              <v-btn  href="/shop" class="white--text " outlined>SHOP NOW</v-btn>
            </div>
          </v-img>
        </v-card>
      </div>
      <div
        class="col-md-6 col-sm-6 col-xs-12"
      >
        <v-card>
          <v-img
            :src="require('../assets/img/home/slider3.jpg')"
            class="white--text align-center"
            gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
            height="400px"
          >
            <h1 class="text-center font-size">New Arrivals</h1>
            <div class="text-center">
              <v-btn  href="/shop" class="white--text" outlined>SHOP NOW</v-btn>
            </div>
          </v-img>
        </v-card>
      </div>
    </div>
    <div class="pl-4 pr-4 row">
      <div
       class="col-md-4 col-sm-4 col-xs-12"
      >
        <v-card outlined>
          <v-img
            :src="require('../assets/img/home/deal2.jpg')"
            class="white--text align-center"
            gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
            height="300px"
          >
            <h1 class="text-center font-size">Lorem & Ipsum</h1>
            <div class="text-center mt-2">
              <v-btn class="white--text caption"  href="/shop" text>SHOP NOW <v-icon class="white--text caption">mdi-arrow-right</v-icon></v-btn>
            </div>
          </v-img>
        </v-card>
      </div>
      <div
        class="col-md-4 col-sm-4 col-xs-12"
      >
        <v-card outlined>
          <v-img
            :src="require('../assets/img/home/deal3.jpg')"
            class="white--text align-center"
            gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
            height="300px"
          >
            <h1 class="text-center font-size">Lorem & Ipsum</h1>
            <div class="text-center mt-2">
              <v-btn class="white--text caption"  href="/shop" text>SHOP NOW <v-icon class="white--text caption">mdi-arrow-right</v-icon></v-btn>
            </div>
          </v-img>
        </v-card>
      </div>
      <div
        class="col-md-4 col-sm-4 col-xs-12"
      >
        <v-card outlined>
          <v-img
            :src="require('../assets/img/home/deal4.jpg')"
            class="white--text align-center"
            gradient="to bottom, rgba(0,0,0,.1), rgba(0,0,0,.5)"
            height="300px"
          >
            <h1 class="text-center font-size">Lorem & Ipsum</h1>
            <div class="text-center mt-2">
              <v-btn class="white--text caption"  href="/shop" text>SHOP NOW <v-icon class="white--text caption">mdi-arrow-right</v-icon></v-btn>
            </div>
          </v-img>
        </v-card>
      </div>
    </div> -->
    <v-container>
      <v-row no-gutters>
        <v-col :cols="12">
          <v-card-text
            class=""
            tile
            outlined
          >
            <v-card-title class="subheading " style="background: #044E7F; color: #fff; border-radius: 5px;">
              Danh mục sản phẩm
            </v-card-title>
            <v-divider></v-divider>
            <div class="row">
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-card
                    to="/shop"
                    style="cursor: pointer;"
                    :elevation="hover ? 16 : 2"
                >
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    contain
                    :src="require('../assets/img/home/Vong_bi.jpg')"
                  >
                    <!-- <v-card-title>Bạc đạn tang trống </v-card-title> -->
                  </v-img>

                  <v-card-text class="text--primary text-center">
                    <h3>Vòng bi - Bạc đạn tang trống</h3>
                    <!-- <div>Baggit, Zara, Fossil</div> -->
                  </v-card-text>

                  <div class="text-center">
                    <!-- <v-btn
                      href="/shop"
                      class="ma-2"
                      outlined
                      style="text-transform: none;"
                      color="orange"
                    >
                      Chi tiết
                    </v-btn> -->
                  </div>
                </v-card>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center" >
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-card
                    to="/shop"
                    :elevation="hover ? 16 : 2"
                    style="cursor: pointer;"
                  >
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    contain
                    :src="require('../assets/img/home/Vong_bi.jpg')"
                  >
                    <!-- <v-card-title>T-Shirt </v-card-title> -->
                  </v-img>

                  <v-card-text class="text--primary text-center">
                    <h3>Vòng bi - Bạc đạn côn</h3>
                    <!-- <div>Baggit, Zara, Fossil</div> -->
                  </v-card-text>

                  <div class="text-center">
                  </div>
                </v-card>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center" >
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-card
                    to="/shop"
                    :elevation="hover ? 16 : 2"
                    style="cursor: pointer;"
                  >
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    :src="require('../assets/img/home/deal3.jpg')"
                  >
                    <!-- <v-card-title>Jeans </v-card-title> -->
                  </v-img>

                  <v-card-text class="text--primary text-center">
                    <h3>Vòng bi - Bạc đạn kim</h3>
                    <!-- <div>Baggit, Zara, Fossil</div> -->
                  </v-card-text>

                  <div class="text-center">
                  </div>
                </v-card>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center" >
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-card
                    to="/shop"
                    :elevation="hover ? 16 : 2"
                    style="cursor: pointer;"
                  >
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    :src="require('../assets/img/home/deal4.jpg')"
                  >
                    <!-- <v-card-title>Shoes </v-card-title> -->
                  </v-img>

                  <v-card-text class="text--primary text-center">
                    <h3>Vòng bi - Bạc đạn đũa</h3>
                    <!-- <div>Baggit, Zara, Fossil</div> -->
                  </v-card-text>

                  <div class="text-center">
                  </div>
                </v-card>
                </v-hover>
              </div>
            </div>

            <div class="row">
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-card
                    to="/shop"
                    :elevation="hover ? 16 : 2"
                    style="cursor: pointer;"
                >
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    :src="require('../assets/img/home/deal1.jpg')"
                  >
                    <!-- <v-card-title>Bags & Purses </v-card-title> -->
                  </v-img>

                  <v-card-text class="text--primary text-center">
                    <h3>Vòng bi -Bạc đạn cầu tự lựa</h3>
                    <!-- <div>Baggit, Zara, Fossil</div> -->
                  </v-card-text>

                  <div class="text-center">
                  </div>
                </v-card>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center" >
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-card
                    to="/shop"
                    :elevation="hover ? 16 : 2"
                    style="cursor: pointer;"
                  >
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    :src="require('../assets/img/home/deal2.jpg')"
                  >
                    <!-- <v-card-title>T-Shirt </v-card-title> -->
                  </v-img>

                  <v-card-text class="text--primary text-center">
                    <h3>Vòng bi - Bạc đạn tiếp xúc góc hai dẫy</h3>
                    <!-- <div>Baggit, Zara, Fossil</div> -->
                  </v-card-text>

                  <div class="text-center">
                  </div>
                </v-card>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center" >
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-card
                    to="/shop"
                    :elevation="hover ? 16 : 2"
                    style="cursor: pointer;"
                  >
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    :src="require('../assets/img/home/deal3.jpg')"
                  >
                    <!-- <v-card-title>Jeans </v-card-title> -->
                  </v-img>

                  <v-card-text class="text--primary text-center">
                    <h3>Vòng bi -Bạc đạn cầu đỡ chặn</h3>
                    <!-- <div>Baggit, Zara, Fossil</div> -->
                  </v-card-text>

                  <div class="text-center">
                  </div>
                </v-card>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center" >
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-card
                    to="/shop"
                    :elevation="hover ? 16 : 2"
                    style="cursor: pointer;"
                  >
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    :src="require('../assets/img/home/deal4.jpg')"
                  >
                   <!--  <v-card-title>Shoes </v-card-title> -->
                  </v-img>

                  <v-card-text class="text--primary text-center">
                    <h3>Vòng bi - Bạc đạn cầu</h3>
                    <!-- <div>Baggit, Zara, Fossil</div> -->
                  </v-card-text>

                  <div class="text-center">
                  </div>
                </v-card>
                </v-hover>
              </div>
            </div>

            <div class="row">
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center">
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-card
                    to="/shop"
                    :elevation="hover ? 16 : 2"
                    style="cursor: pointer;"
                >
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    :src="require('../assets/img/home/deal1.jpg')"
                  >
                    <!-- <v-card-title>Bags & Purses </v-card-title> -->
                  </v-img>

                  <v-card-text class="text--primary text-center">
                    <h3>Vòng bi - Bạc đạn chặn trục</h3>
                    <!-- <div>Baggit, Zara, Fossil</div> -->
                  </v-card-text>

                  <div class="text-center">
                  </div>
                </v-card>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center" >
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-card
                    to="/shop"
                    :elevation="hover ? 16 : 2"
                    style="cursor: pointer;"
                  >
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    :src="require('../assets/img/home/deal2.jpg')"
                  >
                    <!-- <v-card-title>T-Shirt </v-card-title> -->
                  </v-img>

                  <v-card-text class="text--primary text-center">
                    <h3>Vòng bi - Bạc đạn chặn trục tang trống</h3>
                    <!-- <div>Baggit, Zara, Fossil</div> -->
                  </v-card-text>

                  <div class="text-center">
                  </div>
                </v-card>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center" >
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-card
                    to="/shop"
                    :elevation="hover ? 16 : 2"
                    style="cursor: pointer;"
                  >
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    :src="require('../assets/img/home/deal3.jpg')"
                  >
                    <!-- <v-card-title>Jeans </v-card-title> -->
                  </v-img>

                  <v-card-text class="text--primary text-center">
                    <h3>Bạc đạn tang trống</h3>
                    <!-- <div>Baggit, Zara, Fossil</div> -->
                  </v-card-text>

                  <div class="text-center">
                  </div>
                </v-card>
                </v-hover>
              </div>
              <div class="col-12 col-md-3 col-sm-6 col-xs-6 text-center" >
                <v-hover
                  v-slot:default="{ hover }"
                  open-delay="200"
                >
                  <v-card
                    to="/shop"
                    :elevation="hover ? 16 : 2"
                    style="cursor: pointer;"
                  >
                  <v-img
                    class="white--text align-end"
                    height="200px"
                    :src="require('../assets/img/home/deal4.jpg')"
                  >
                    <!-- <v-card-title>Shoes </v-card-title> -->
                  </v-img>

                  <v-card-text class="text--primary text-center">
                    <h3>Bạc đạn tang trống</h3>
                    <!-- <div>Baggit, Zara, Fossil</div> -->
                  </v-card-text>

                  <div class="text-center">
                  </div>
                </v-card>
                </v-hover>
              </div>
            </div>
          </v-card-text>
        </v-col>

        <v-col :cols="12">
          <v-card-text
            class=""
            tile
            outlined
          >
            <v-card-title class="subheading " style="background: #044E7F; color: #fff; border-radius: 5px;">
              Giới thiệu
            </v-card-title>
            <v-divider></v-divider>
            <div class="row">
              <div class="col-12 col-md-12 col-sm-12 col-xs-12 text-center">
                <v-img
                  contain
                  class="white--text align-end"
                  :src="require('../assets/img/home/intro2.png')"
                  >
                </v-img>
              </div>
              <div class="col-12 col-md-12 col-sm-12 col-xs-12">
                <div style="text-align:justify;color:#383838;">
                  <h3>
                    GIB Việt Nam - 10 năm xây dựng và trưởng thành
                  </h3>
                  <div>
                    Tiền thân là một cửa hàng kinh doanh vòng bi công nghiệp, với hơn 10 năm trong thị trường, GIB vươn lên trở thành top 10 công ty phân phối vòng bi hàng đầu Việt Nam.
                  </div>
                  <div>
                    Để hiểu hơn về GIB Việt Nam, chúng ta hãy cùng điểm qua vài dấu mốc lịch sử hình thành và phát triển của Cty trách nhiệm hữu hạn GIB Việt Nam thịnh vượng ngày nay:
                  </div>
                  <div>
                    - Tháng 6 - 2006, GIB Việt Nam tiền thân là một cửa hàng kinh doanh vòng bi công nghiệp, nhen nhóm từ niềm đam mê cháy bỏng của chàng sinh viên cơ khí Bách Khoa giầu nhiệt huyết mang tên Nguyễn Thành Trung.
                  </div>
                  <div>
                    - Tháng 8 - 2008, nhận thấy thị trường không như những gì tưởng tượng của một chàng sinh viên, Nguyễn Thành Trung khi ấy đã quyết định đầu quân cho một cty chuyên cung cấp vòng bi vào thị trường Việt Nam, để rồi trở thành trợ lý Giám Đốc Kinh Doanh khi ấy…chính thức bước chân vào tìm hiểu thị trường chuyên nghiệp.
                  </div>
                  <div>
                    - Tháng 10 - 2009, hiểu hơn về thị trường và nhu cầu vòng bi công nghiệp tại Việt Nam, Nguyễn Thành Trung trở về nâng cấp cửa hành kinh doanh của mình, bắt đầu có những đối tác và khách hàng thường xuyên đặt hàng với số lượng lớn. Nguyễn Thành Trung nhanh chóng đáp ứng nhu cầu thị trường, dần có tiếng trong giới cung cấp vòng bi công nghiệp trong nước.
                  </div>
                  <div>
                    Sau hơn 4 năm mày mò tìm hiểu, rồi chiếm lĩnh từng phân khúc thị trường, chàng trai Nguyễn Thành Trung khi ấy nhận ra, để hạ giá thành sản phẩm, không thể mãi đi lòng vòng ở thị trường nhỏ bé trong nước:
                  </div>
                  <div>
                    -Tháng  9 - 2010, Công ty trách nhiệm hữu hạn GIB Việt Nam chính thức được thành lập do Nguyễn Thành Trung làm Giám đốc. GIB Việt Nam chính thức bước chân ra thị trường quốc tế, nhập khẩu trực tiếp vòng bi chính hãng từ các hãng vòng bi hàng đầu thế giới, trở thành đối tác thân thiết chiến lược của các tổng kho NSK, SKF… cho tới ngày nay.
                  </div>
                  <div>
                    Với hơn 6 năm nhập khẩu trực tiếp vòng bi chính hãng từ: Mỹ, Nhật Bản, Singapore…phân phối vào thị trường Việt Nam. GIB đã trở thành một trong số top 10 các công ty phân phối vòng bi trên thị trường Việt Nam. Cung cấp chủ yếu cho nhà bán sỉ,  đơn vị OEM và thì trường thay thế, phục vụ đông đảo khách hàng là các tập đoàn lớn có yêu cầu khắt khe trên nhiều lĩnh vực sản xuất công nghiệp như: Khai khoáng, Sản xuất Xi măng, Thủy Điện, Gang Thép, Sản xuất Phân Bón, Chế biến gỗ, Sản xuất giấy, Mía Đường, Quạt thông gió công nghiệp….
                  </div>
                  <div>
                    Sau 10 năm nỗ lực không ngừng, luôn đáp ứng mọi nhu cầu về vòng bi của khách hàng với nguyên tắc phục vụ đặc biệt,  luôn cung cấp hàng chính hãng-phục vụ không giới hạn không gian và thời gian. Trong khi đó giá sản phẩm luôn thấp hơn nhiều các đơn vị danh tiếng khác, giúp khách hàng tiết kiệm ngân sách trong sản xuất mà chất lượng không đổi. GIB Việt Nam đã may mắn trở thành đối tác tin cậy của hàng loạt các tập đoàn lớn.
                  </div>
                </div>
              </div>
            </div>
          </v-card-text>
        </v-col>
      </v-row>
    </v-container>

    <div style="padding: 30px 0; background-color: #003586;" class="row whyBox">
      <div class="col-12 col-md-12 col-sm-12 col-xs-12 text-center">
        <h1 class="box-heading">Mua bán Vòng bi bạc đạn SKF chính hãng uy tín số 1 Việt Nam</h1>
        <p style="font-weight: 300; font-size:22px; color:#fff; margin-bottom: 0;">"Vongbimib.com - Tìm đúng nơi, mua đúng chỗ"</p>
      </div>
      <v-container>
        <div class="row">
          <div class="col-4 col-md-4 col-sm-12 col-xs-12 _item">
            <div class="icon _icon1">
              <v-img
              contain
              class="white--text align-end"
              :src="require('../assets/img/home/why-icon-1.png')"
              >
            </v-img>
            </div>
            <div class="info">
              <h2 class="title" itemprop="name"><i class="fas fa-caret-square-right" style="color: #38c500; padding-right: 5px;
              "></i>Online - Offline</h2>
              <div class="desc" itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                <span itemprop="text">
                  Sản phẩm được kinh doanh linh hoạt, Online và Offline. Bạn có thể mua hàng trực tiếp theo cách truyền thống hoặc Online, Giúp bạn tiết kiệm thời gian và tiền bạc.
                </span>
              </div>
            </div>
          </div>

          <div class="col-4 col-md-4 col-sm-12 col-xs-12 _item">
            <div class="icon _icon1">
              <v-img
              contain
              class="white--text align-end"
              :src="require('../assets/img/home/why-icon-2.png')"
              >
            </v-img>
            </div>
            <div class="info">
              <h2 class="title" itemprop="name"><i class="fas fa-caret-square-right" style="color: #38c500; padding-right: 5px;
              "></i>SẢN PHẨM SKF CHÍNH HÃNG</h2>
              <div class="desc" itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                <span itemprop="text">
                  Phân phối sản phẩm chính hãng, Chúng tôi cam kết hoàn tiền gấp 100 lần giá trị đơn hàng nếu phát hiện hàng giả, hàng nhái từ vongbi.com
                </span>
              </div>
            </div>
          </div>

          <div class="col-4 col-md-4 col-sm-12 col-xs-12 _item">
            <div class="icon _icon1">
              <v-img
              contain
              class="white--text align-end"
              :src="require('../assets/img/home/why-icon-3.png')"
              >
            </v-img>
            </div>
            <div class="info">
              <h2 class="title" itemprop="name"><i class="fas fa-caret-square-right" style="color: #38c500; padding-right: 5px;
              "></i>Online - Offline</h2>
              <div class="desc" itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                <span itemprop="text">
                  Mọi sản phẩm bán ra đều có thông tin rõ ràng, minh bạch cũng như các chế độ sau bán hàng mà chỉ nhà phân phối ủy quyền mới có.
                </span>
              </div>
            </div>
          </div>

          <div class="col-4 col-md-4 col-sm-12 col-xs-12 _item">
            <div class="icon _icon1">
              <v-img
              contain
              class="white--text align-end"
              :src="require('../assets/img/home/why-icon-4.png')"
              >
            </v-img>
            </div>
            <div class="info">
              <h2 class="title" itemprop="name"><i class="fas fa-caret-square-right" style="color: #38c500; padding-right: 5px;
              "></i>BẢO HÀNH CHÍNH HÃNG</h2>
              <div class="desc" itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                <span itemprop="text">
                  Sản phẩm SKF do chúng tôi bán ra đều được bảo hành chính hãng SKF, Cơ chế bảo hành đổi mới linh hoạt. Hỗ trợ tối đa lợi ích của Khách hàng.
                </span>
              </div>
            </div>
          </div>

          <div class="col-4 col-md-4 col-sm-12 col-xs-12 _item">
            <div class="icon _icon1">
              <v-img
              contain
              class="white--text align-end"
              :src="require('../assets/img/home/why-icon-5.png')"
              >
            </v-img>
            </div>
            <div class="info">
              <h2 class="title" itemprop="name"><i class="fas fa-caret-square-right" style="color: #38c500; padding-right: 5px;
              "></i>HỖ TRỢ KỸ THUẬT 24/7</h2>
              <div class="desc" itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                <span itemprop="text">
                  Đội ngũ bán hàng & kỹ thuật của chúng tôi luôn sẵn sàng phục vụ và hỗ trợ bạn mọi lúc mọi nơi tất cả các ngày trong tuần 24/24.
                </span>
              </div>
            </div>
          </div>

          <div class="col-4 col-md-4 col-sm-12 col-xs-12 _item">
            <div class="icon _icon1">
              <v-img
              contain
              class="white--text align-end"
              :src="require('../assets/img/home/why-icon-6.png')"
              >
            </v-img>
            </div>
            <div class="info">
              <h2 class="title" itemprop="name"><i class="fas fa-caret-square-right" style="color: #38c500; padding-right: 5px;
              "></i>GIAO HÀNG TOÀN QUỐC</h2>
              <div class="desc" itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                <span itemprop="text">
                  Cho dù bạn ở đâu? chúng tôi luôn sẵn sàng được phục vụ nhu cầu của bạn với chế độ giao hàng và thanh toán linh hoạt trên toàn quốc.
                </span>
              </div>
            </div>
          </div>
        </div>
      </v-container>
    </div>

    <v-card  class="hotline" >
      <v-container>
        <v-row no-gutters>
          <v-col class="col-12 col-md-12 col-sm-12 text-center">
            <div class="container">
              <span class="dot" style="margin-left: 5px; margin-top: -4px;">
                <span class="ping"></span>
              </span>
              <span style="font-weight:300; color: #fff;">Hotline hỗ trợ báo giá 24/7</span>
              <!-- <i class="fas fa-phone-square" style="color:#38c500;padding-left: 18px"></i> -->
              <a href="tel:0921 345 345" title="báo giá vòng bi SKF chính hãng" rel="nofollow">
                <v-icon style="font-size: 17px; padding-left: 18px;">mdi-phone-classic</v-icon>
                <span style="color: #fff; font-family: 'Bebas Neue'; font-size: 18px;">0921 345 345</span>
              </a>
              <!-- <i class="fas fa-phone-square" style="color:#38c500;padding-left: 18px;"></i> -->
              <a href="tel:076 66 55 386" title="báo giá vòng bi SKF chính hãng" rel="nofollow">
                <v-icon style="font-size: 17px; padding-left: 18px;">mdi-phone-classic</v-icon>
                <span style="color: #fff; font-family: 'Bebas Neue'; font-size: 18px;">076 66 55 386</span>
              </a>
              <!-- <i class="fas fa-phone-square" style="color:#38c500;padding-left: 18px;"></i> -->
              <a href="tel:0763 356 999" title="báo giá vòng bi SKF chính hãng" rel="nofollow">
                <v-icon style="font-size: 17px; padding-left: 18px;">mdi-phone-classic</v-icon>
                <span style="color: #fff; font-family: 'Bebas Neue'; font-size: 18px;">0763 356 999</span>
              </a>
            </div>
          </v-col>
          <!-- <v-col class="col-12 col-md-4 col-sm-12">
            <v-row >
              <v-col class="col-12 col-sm-3 pr-4" align="right">
                <v-icon class="display-2">mdi-truck</v-icon>
              </v-col>
              <v-col class="col-12 col-sm-9 pr-4">
                <h3 class="font-weight-light">FREE SHIPPING & RETURN</h3>
                              <p class="font-weight-thin">Free Shipping over $300</p>
              </v-col>
            </v-row>
          </v-col>
          <v-col class="col-12 col-md-4 col-sm-12">
            <v-row >
              <v-col class="col-12 col-sm-3 pr-4" align="right">
                <v-icon class="display-2">mdi-cash-usd</v-icon>
              </v-col>
              <v-col  class="col-12 col-sm-9 pr-4">
                <h3 class="font-weight-light">MONEY BACK GUARANTEE</h3>
                <p class="font-weight-thin">30 Days Money Back Guarantee</p>
              </v-col>
            </v-row>
          </v-col>
          <v-col class="col-12 col-md-4 col-sm-12">
            <v-row>
              <v-col class="col-12 col-sm-3 pr-4" align="right">
                <v-icon class="display-2">mdi-headset</v-icon>
              </v-col>
              <v-col  class="col-12 col-sm-9 pr-4">
                <h3 class="font-weight-light">020-800-456-747</h3>
                <p class="font-weight-thin">24/7 Available Support</p>
              </v-col>
            </v-row>
          </v-col> -->
        </v-row>
      </v-container>
    </v-card>
  </div>
</template>

<script>
    export default {
        data () {
            return {
                items: [
                    { title: 'Click Me' },
                    { title: 'Click Me' },
                    { title: 'Click Me' },
                    { title: 'Click Me 2' },
                ],
                activeBtn: 1,
                colors: [
                    'indigo',
                    'warning',
                    'pink darken-2',
                    'red lighten-1',
                    'deep-purple accent-4',
                ],
                slides: [
                    'First',
                    'Second',
                    'Third',
                    'Fourth',
                    'Fifth',
                ],
            }
        },
    }
</script>
<style>
  .v-card--reveal {
    align-items: center;
    bottom: 0;
    justify-content: center;
    opacity: .5;
    position: absolute;
    width: 100%;
  }
  .whyBox .box-heading {
    display: inline-block;
    text-align: center;
    text-transform: uppercase;
    color: #fff;
    margin: 0;
    font-weight: 700;
    font-size: 24px;
  }
  .whyBox ._item {
    padding-top: 40px;
    padding-botom: 50px;
  }
  .whyBox ._item .info {
    overflow: hidden;
    padding-top: 10px;
    background: #003586 !important;
  }
  .whyBox ._item .info .title {
    font-size: 14px !important;
    color: #fff;
    text-transform: uppercase;
    margin: 0;
    padding: 0 0 0px;
    font-weight: 700;
  }

  .whyBox ._item .icon {
    margin-top: 20px;
    width: 60px;
    height: 60px;
    float: left;
    margin-right: 15px;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: contain;
  }

  .whyBox ._item .info .desc {
    font-size: 11px;
    color: #fff;
    margin: 0;
    padding: 0 0 10px;
    padding-top: 0px;
    padding-right: 0px;
    padding-bottom: 10px;
    padding-left: 0px;
    font-weight: 300;
  }
</style>

