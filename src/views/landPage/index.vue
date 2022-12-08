<template>
  <div class="landPage-container">
    <!-- 顶部 --S  -->
    <div class="landPage_nav">
      <div class="central-plate">
        <!--   logo     -->
        <div class=" flex-space-between">
          <div class="nav_logo">
            <picture>
              <source media="(max-width: 751px)" srcset="/@/assets/com/img/landPage/logoM.png">
              <source media="(min-width: 751px)" srcset="/@/assets/com/img/landPage/logoW.png">
              <img src="cat.jpg" alt="cat">
            </picture>
          </div>
          <div class="nav_tablanguage flex-space-between">
            <div class="nav_tablanguage_icon"></div>
            <div>English</div>
            <!--        <picture>-->
            <!--          <source media="(max-width: 751px)" srcset="/@/assets/com/img/landPage/globalM.png">-->
            <!--          <source media="(min-width: 751px)" srcset="/@/assets/com/img/landPage/globalW.png">-->
            <!--          <img src="cat.jpg" alt="cat">-->
            <!--        </picture>-->
            <!--          <div >xunaxian</div>-->
            <!--        <el-select v-model="state.langvage" class="m-2" placeholder="English" size="large">-->
            <!--          <el-option-->
            <!--              v-for="item in state.options"-->
            <!--              :key="item.value"-->
            <!--              :label="item.label"-->
            <!--              :value="item.value"-->
            <!--          />-->
            <!--        </el-select>-->
          </div>
        </div>
        <!--   form     -->
        <div class="nav_content flex-space-between">
          <div class="nav_title">
            <div class="nav_title_head">Content Management and Protection platform</div>
            <div class="nav_title_sub">protection platform can help your content discover and remove piracy ，find back lost cotent and reputation</div>
          </div>
          <div class="nav_form">lllll</div>
        </div>
      </div>
    </div>
    <!-- How Whaleip solution works   -->
    <div class="howWork central-plate">
      <div class="howWork_title">How Whaleip solution works</div>
      <!-- 卡片一     -->
      <div class="flex-space-between howWork_content">
        <div class="howWork_card_lf">
          <div class="card_title">Track</div>
          <div class="card_subtitle">Rapidly detect pirated content anywhere online</div>
          <div class="second_title flex-space-between">
            <div class="second_title_icon"></div>
            <div class="second_title_content">
              <div class="second_title_content_main">Machine infringement monitoring</div>
              <div class="second_title_content_sub">Let the robot 7*24h search an find potential infringements for
                you
              </div>
            </div>
          </div>
          <div class="second_title flex-space-between">
            <div class="second_title_icon second_title_icon_two"></div>
            <div class="second_title_content">
              <div class="second_title_content_main">Largest Database of Websites</div>
              <div class="second_title_content_sub">regularly upload copyright-infringing content impacting your
                business
              </div>
            </div>
          </div>
          <div class="second_title_one"></div>
        </div>
        <div class="howWork_card_ri">
          <picture>
            <source media="(max-width: 751px)" srcset="/@/assets/com/img/landPage/howWorkM1.png">
            <source media="(min-width: 751px)" srcset="/@/assets/com/img/landPage/howWorkW1.png">
            <img class="howWork_card_img" src="cat.jpg" alt="cat">
          </picture>
        </div>
      </div>
      <!-- 卡片二     -->
      <div class="flex-space-between howWork_content howWork_content_reverse">
        <div class="howWork_card_lf_reverse">
          <picture>
            <source media="(max-width: 751px)" srcset="/@/assets/com/img/landPage/howWorkM2.png">
            <source media="(min-width: 751px)" srcset="/@/assets/com/img/landPage/howWorkW2.png">
            <img class="howWork_card_img" src="cat.jpg" alt="cat">
          </picture>
        </div>
        <div class="howWork_card_ri_reverse">
          <div class="card_title">Validate</div>
          <div class="card_subtitle">AI model infringement judgment，or decide one by one</div>
          <div class="second_title flex-space-between second_title_reverse">
            <div class="second_title_icon"></div>
            <div class="second_title_content second_title_content_mains">
              <div class="second_title_content_main">Image recognition and text comparison</div>
              <div class="second_title_content_sub">AI-based image recognition and text analysis technology to deep-search web with accuracy</div>
            </div>
          </div>
          <div class="second_title flex-space-between second_title_reverse">
            <div class="second_title_icon second_title_icon_two"></div>
            <div class="second_title_content second_title_content_mains">
              <div class="second_title_content_main">optional human-in-the-loop review</div>
              <div class="second_title_content_sub">Manual confirmation of piracy to avoid accidental injury</div>
            </div>
          </div>
        </div>
      </div>
      <!-- 卡片三     -->
      <div class="flex-space-between howWork_content">
        <div class="howWork_card_lf">
          <div class="card_title">Delete</div>
          <div class="card_subtitle">continuous takedown of infringing contents</div>
          <div class="second_title flex-space-between">
            <div class="second_title_icon"></div>
            <div class="second_title_content">
              <div class="second_title_content_main">Automation rules</div>
              <div class="second_title_content_sub">Enforce against copyright infringement automatically submitted to search engines</div>
            </div>
          </div>
          <div class="second_title flex-space-between">
            <div class="second_title_icon second_title_icon_two"></div>
            <div class="second_title_content">
              <div class="second_title_content_main">Removal follow-up</div>
              <div class="second_title_content_sub">Piracy experts take action to further eradicate piracy</div>
            </div>
          </div>
          <div class="second_title_one"></div>
        </div>
        <div class="howWork_card_ri">
          <picture>
            <source media="(max-width: 751px)" srcset="/@/assets/com/img/landPage/howWorkM3.png">
            <source media="(min-width: 751px)" srcset="/@/assets/com/img/landPage/howWorkW3.png">
            <img class="howWork_card_img" src="cat.jpg" alt="cat">
          </picture>
        </div>
      </div>
      <!-- 卡片四    -->
      <div class="flex-space-between howWork_content howWork_content_reverse">
        <div class="howWork_card_lf_reverse">
          <picture>
            <source media="(max-width: 751px)" srcset="/@/assets/com/img/landPage/howWorkM4.png">
            <source media="(min-width: 751px)" srcset="/@/assets/com/img/landPage/howWorkW4.png">
            <img class="howWork_card_img" src="cat.jpg" alt="cat">
          </picture>
        </div>
        <div class="howWork_card_ri_reverse">
          <div class="card_title">Analyze</div>
          <div class="card_subtitle">Copyright Protection Report</div>
          <div class="second_title flex-space-between second_title_reverse">
            <div class="second_title_icon"></div>
            <div class="second_title_content second_title_content_mains">
              <div class="second_title_content_main">Protect data in real time</div>
              <div class="second_title_content_sub">View real-time enforcement results and track down infringers to the source</div>
            </div>
          </div>
          <div class="second_title flex-space-between second_title_reverse">
            <div class="second_title_icon second_title_icon_two"></div>
            <div class="second_title_content second_title_content_mains">
              <div class="second_title_content_main">Performance dashboards</div>
              <div class="second_title_content_sub">Quickly understand your anti-piracy coverage</div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- works that   -->
    <div class="works_that">
      <div class="central-plate central-plate-that">
        <div class="works_that_title">Works that <div style="color: rgba(32, 94, 255, 1)">support protection</div></div>
        <div class="works_that_card flex-space-between">
          <div class="that_card" v-for="item in state.workThatList" :key="item.title">
            <picture>
              <source media="(max-width: 751px)" :srcset="item.imgM">
              <source media="(min-width: 751px)" :srcset="item.imgW">
              <img class="that_card_img" src="cat.jpg" alt="cat">
            </picture>
            <div class="that_card_foot">{{item.title}}</div>
          </div>
        </div>
      </div>
    </div>
    <!-- works protect  -->
    <div class="works_that work_protect">
      <div class="central-plate central-plate-that">
        <div class="works_that_title">We protect your <div style="color: rgba(32, 94, 255, 1)">content on platforms</div></div>
        <div class="works_that_card flex-space-between">
          <div class="that_card" v-for="(item,index) in state.workProtect" :key="index">
            <picture>
              <source media="(max-width: 751px)" :srcset="item.imgTopW">
              <source media="(min-width: 751px)" :srcset="item.imgTopM">
              <img class="protect_card_img" src="cat.jpg" alt="cat">
            </picture>
            <div class="protect_card_foot">{{item.title}}</div>
              <div class="protect_card_img_list flex-space-between">
                <picture v-for="(items,indexs) in item.imgList" :key="indexs">
                  <source media="(max-width: 751px)" :srcset="items.imglistW">
                  <source media="(min-width: 751px)" :srcset="items.imglistW">
                  <img class="protect_card_img_list_demo" src="cat.jpg" alt="cat">
                </picture>
                <span>...</span>
              </div>
            </div>
        </div>
      </div>
    </div>
    <!-- Why us   -->
    <div class="works_that why_us">
      <div class="central-plate central-plate-why">
        <div class="works_that_title why_us_title">Why Us</div>
        <div class="flex-space-between">
<!--          <div class="that_card" >-->
<!--            -->
<!--          </div>-->
          <div class="that_card" v-for="(item,index) in state.whyUsList" :key="index">
            <div class="why_us_num">{{item.nums}}</div>
            <div class="why_us_num_sutitle">{{item.title}}</div>
            <div class="why_us_num_title">{{item.subtitle}}</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup lang="ts" name="landPageIndex">
import { reactive } from "vue";
import workthatImgM1 from "/@/assets/com/img/landPage/workthatM1.png"
import workthatImgW1 from "/@/assets/com/img/landPage/workthatW1.png"
import workthatImgM2 from "/@/assets/com/img/landPage/workthatM2.png"
import workthatImgW2 from "/@/assets/com/img/landPage/workthatW2.png"
import workthatImgM3 from "/@/assets/com/img/landPage/workthatM3.png"
import workthatImgW3 from "/@/assets/com/img/landPage/workthatW3.png"
import workthatImgM4 from "/@/assets/com/img/landPage/workthatM4.png"
import workthatImgW4 from "/@/assets/com/img/landPage/workthatW4.png"
import workthatImgM5 from "/@/assets/com/img/landPage/workthatM5.png"
import workthatImgW5 from "/@/assets/com/img/landPage/workthatW5.png"
import shopImgW from "/@/assets/com/img/landPage/index/shopW.png"
import shopImgM from "/@/assets/com/img/landPage/index/shopW.png"
import shopListImgW1 from "/@/assets/com/img/landPage/index/shop_listW1.png"
import shopListImgM1 from "/@/assets/com/img/landPage/index/shop_listM1.png"
import shopListImgW2 from "/@/assets/com/img/landPage/index/shop_listW2.png"
import shopListImgM2 from "/@/assets/com/img/landPage/index/shop_listM1.png"
import shopListImgW3 from "/@/assets/com/img/landPage/index/shop_listW3.png"
import shopListImgM3 from "/@/assets/com/img/landPage/index/shop_listM3.png"
import shopListImgW4 from "/@/assets/com/img/landPage/index/shop_listW4.png"
import shopListImgM4 from "/@/assets/com/img/landPage/index/shop_listM4.png"
import shopListImgW5 from "/@/assets/com/img/landPage/index/shop_listW5.png"
import shopListImgM5 from "/@/assets/com/img/landPage/index/shop_listM5.png"
import shopListImgW6 from "/@/assets/com/img/landPage/index/shop_listW6.png"
import shopListImgM6 from "/@/assets/com/img/landPage/index/shop_listM6.png"
import socialImgW from "/@/assets/com/img/landPage/index/socialW.png"
import socialImgM from "/@/assets/com/img/landPage/index/socialW.png"
import socialListImgW1 from "/@/assets/com/img/landPage/index/social_listW1.png"
import socialListImgM1 from "/@/assets/com/img/landPage/index/social_listM1.png"
import socialListImgW2 from "/@/assets/com/img/landPage/index/social_listW2.png"
import socialListImgM2 from "/@/assets/com/img/landPage/index/social_listM1.png"
import socialListImgW3 from "/@/assets/com/img/landPage/index/social_listW3.png"
import socialListImgM3 from "/@/assets/com/img/landPage/index/social_listM3.png"
import socialListImgW4 from "/@/assets/com/img/landPage/index/social_listW4.png"
import socialListImgM4 from "/@/assets/com/img/landPage/index/social_listM4.png"
import socialListImgW5 from "/@/assets/com/img/landPage/index/social_listW5.png"
import socialListImgM5 from "/@/assets/com/img/landPage/index/social_listM5.png"
import socialListImgW6 from "/@/assets/com/img/landPage/index/social_listW6.png"
import socialListImgM6 from "/@/assets/com/img/landPage/index/social_listM6.png"
import searchImgW from "/@/assets/com/img/landPage/index/searchW.png"
import searchImgM from "/@/assets/com/img/landPage/index/searchW.png"
import searchListImgW1 from "/@/assets/com/img/landPage/index/search_listW1.png"
import searchListImgM1 from "/@/assets/com/img/landPage/index/search_listM1.png"
import searchListImgW2 from "/@/assets/com/img/landPage/index/search_listW2.png"
import searchListImgM2 from "/@/assets/com/img/landPage/index/search_listM1.png"
import searchListImgW3 from "/@/assets/com/img/landPage/index/search_listW3.png"
import searchListImgM3 from "/@/assets/com/img/landPage/index/search_listM3.png"
import searchListImgW4 from "/@/assets/com/img/landPage/index/search_listW4.png"
import searchListImgM4 from "/@/assets/com/img/landPage/index/search_listM4.png"
import searchListImgW5 from "/@/assets/com/img/landPage/index/search_listW5.png"
import searchListImgM5 from "/@/assets/com/img/landPage/index/search_listM5.png"
import searchListImgW6 from "/@/assets/com/img/landPage/index/search_listW6.png"
import searchListImgM6 from "/@/assets/com/img/landPage/index/search_listM6.png"

import videoImgW from "/@/assets/com/img/landPage/index/videoW.png"
import videoImgM from "/@/assets/com/img/landPage/index/videoW.png"
import videoListImgW1 from "/@/assets/com/img/landPage/index/video_listW1.png"
import videoListImgM1 from "/@/assets/com/img/landPage/index/video_listM1.png"
import videoListImgW2 from "/@/assets/com/img/landPage/index/video_listW2.png"
import videoListImgM2 from "/@/assets/com/img/landPage/index/video_listM1.png"
import videoListImgW3 from "/@/assets/com/img/landPage/index/video_listW3.png"
import videoListImgM3 from "/@/assets/com/img/landPage/index/video_listM3.png"
import videoListImgW4 from "/@/assets/com/img/landPage/index/video_listW4.png"
import videoListImgM4 from "/@/assets/com/img/landPage/index/video_listM4.png"
import videoListImgW5 from "/@/assets/com/img/landPage/index/video_listW5.png"
import videoListImgM5 from "/@/assets/com/img/landPage/index/video_listM5.png"
import videoListImgW6 from "/@/assets/com/img/landPage/index/video_listW6.png"
import videoListImgM6 from "/@/assets/com/img/landPage/index/video_listM6.png"

import shortImgW from "/@/assets/com/img/landPage/index/shortW.png"
import shortImgM from "/@/assets/com/img/landPage/index/shortW.png"
import shortListImgW1 from "/@/assets/com/img/landPage/index/short_listW1.png"
import shortListImgM1 from "/@/assets/com/img/landPage/index/short_listM1.png"
import shortListImgW2 from "/@/assets/com/img/landPage/index/short_listW2.png"
import shortListImgM2 from "/@/assets/com/img/landPage/index/short_listM1.png"
import shortListImgW3 from "/@/assets/com/img/landPage/index/short_listW3.png"
import shortListImgM3 from "/@/assets/com/img/landPage/index/short_listM3.png"
import shortListImgW4 from "/@/assets/com/img/landPage/index/short_listW4.png"
import shortListImgM4 from "/@/assets/com/img/landPage/index/short_listM4.png"
import shortListImgW5 from "/@/assets/com/img/landPage/index/short_listW5.png"
import shortListImgM5 from "/@/assets/com/img/landPage/index/short_listM5.png"
import shortListImgW6 from "/@/assets/com/img/landPage/index/short_listW6.png"
import shortListImgM6 from "/@/assets/com/img/landPage/index/short_listM6.png"


const state = reactive({
  langvage:'',
  options: [
    {
      value: 1,
      label: 'CHINESE'
    },
    {
      value: 2,
      label: 'ENGLISH'
    }
  ],
  workThatList:[
    {
      title:'VIDEO/CINEMA',
      imgW: workthatImgW1,
      imgM: workthatImgM1,
    },
    {
      title:'LIVE EVENTS & STREAMING',
      imgW: workthatImgW2,
      imgM: workthatImgM2,
    },
    {
      title:'PICTURE',
      imgW: workthatImgW3,
      imgM: workthatImgM3,
    },
    {
      title:'BRAND',
      imgW: workthatImgW4,
      imgM: workthatImgM4,
    },
    {
      title:'LEARNING AND INFO PRODUCT',
      imgW: workthatImgW5,
      imgM: workthatImgM5,
    }
  ],
  workProtect: [
    {
      imgTopW: shopImgW,
      imgTopM: shopImgM,
      title: 'Shopping platform',
      imgList:[
        {
          imglistW: shopListImgW1,
          imglistM: shopListImgM1,
        },
        {
          imglistW: shopListImgW2,
          imglistM: shopListImgM2,
        },
        {
          imglistW: shopListImgW3,
          imglistM: shopListImgM3,
        },
        {
          imglistW: shopListImgW4,
          imglistM: shopListImgM4,
        },
        {
          imglistW: shopListImgW5,
          imglistM: shopListImgM5,
        },
        {
          imglistW: shopListImgW6,
          imglistM: shopListImgM6,
        },
      ]
    },
    {
      imgTopW: socialImgW,
      imgTopM: socialImgM,
      title: 'Social media platforms',
      imgList:[
        {
          imglistW: socialListImgW1,
          imglistM: socialListImgM1,
        },
        {
          imglistW: socialListImgW2,
          imglistM: socialListImgM2,
        },
        {
          imglistW: socialListImgW3,
          imglistM: socialListImgM3,
        },
        {
          imglistW: socialListImgW4,
          imglistM: socialListImgM4,
        },
        {
          imglistW: socialListImgW5,
          imglistM: socialListImgM5,
        },
        {
          imglistW: socialListImgW6,
          imglistM: socialListImgM6,
        },
      ]
    },
    {
      imgTopW: searchImgW,
      imgTopM: searchImgM,
      title: 'Search engine',
      imgList:[
        {
          imglistW: searchListImgW1,
          imglistM: searchListImgM1,
        },
        {
          imglistW: searchListImgW2,
          imglistM: searchListImgM2,
        },
        {
          imglistW: searchListImgW3,
          imglistM: searchListImgM3,
        },
        {
          imglistW: searchListImgW4,
          imglistM: searchListImgM4,
        },
        {
          imglistW: searchListImgW5,
          imglistM: searchListImgM5,
        },
        {
          imglistW: searchListImgW6,
          imglistM: searchListImgM6,
        },
      ]
    },
    {
      imgTopW: videoImgW,
      imgTopM: videoImgM,
      title: 'Video platform',
      imgList:[
        {
          imglistW: videoListImgW1,
          imglistM: videoListImgM1,
        },
        {
          imglistW: videoListImgW2,
          imglistM: videoListImgM2,
        },
        {
          imglistW: videoListImgW3,
          imglistM: videoListImgM3,
        },
        {
          imglistW: videoListImgW4,
          imglistM: videoListImgM4,
        },
        {
          imglistW: videoListImgW5,
          imglistM: videoListImgM5,
        },
        {
          imglistW: videoListImgW6,
          imglistM: videoListImgM6,
        },
      ]
    },
    {
      imgTopW: shortImgW,
      imgTopM: shortImgM,
      title: 'Short video platform',
      imgList:[
        {
          imglistW: shortListImgW1,
          imglistM: shortListImgM1,
        },
        {
          imglistW: shortListImgW2,
          imglistM: shortListImgM2,
        },
        {
          imglistW: shortListImgW3,
          imglistM: shortListImgM3,
        },
        {
          imglistW: shortListImgW4,
          imglistM: shortListImgM4,
        },
        {
          imglistW: shortListImgW5,
          imglistM: shortListImgM5,
        },
        {
          imglistW: shortListImgW6,
          imglistM: shortListImgM6,
        },
      ]
    }
  ],
  whyUsList: [
    {
      nums:'92% +',
      title:'Removal Success Rate',
      subtitle:'Achieve consistently high removal success rate using AI technology with an optional human-in-the-loop review.',
    },
    {
      nums:'10000 +',
      title:'monitoring Asian platform',
      subtitle: 'Auto-detect and auto-report by monitoring the online Asian marketplaces around the globe 24/7.'
    },
    {
      nums:'100%',
      title:'coverage of the Asian market',
      subtitle: 'Monitor Asian online marketplaces, social media, video channels and uncover millions of pirated products'
    },
    {
      nums:'70%',
      title:'cost reduction',
      subtitle: 'Remove piracy through automatic machine monitoring, reducing 70% of manual discovery and removal costs'
    }

  ]
});
</script>

<style scoped lang="scss">
$blue1:rgba(32, 94, 255, 1);
$black1:rgba(51, 51, 51, 1);
.landPage-container {
  width: 100%;
  background: var(--el-color-white);
  .landPage_nav {
    width: 100%;
    .nav_logo {
      img{
        width: 1.97rem;
        height: .38rem;
      }
    }
    .nav_tablanguage {
      width: 1.78rem;
      height: .54rem;
      line-height: .54rem;
      color: #ffffff;
      border: 1px solid #ffffff;
      border-radius: .27rem;
      background-color: rgba(255, 255, 255, 0);
      .nav_tablanguage_icon{

      }
    }
    .nav_content{
      color: #ffffff;
      .nav_title{
        .nav_title_head{
          font-family: Arial Black-Regular, Arial Black;
        }
        .nav_title_sub {
          font-family: Work Sans-Regular, Work Sans;
        }
        font-weight: 400;
        color: #FFFFFF;
      }
    }
  }
  .howWork{
    .howWork_title{
      font-family: Arial Black-Regular, Arial Black;
      font-weight: 400;
      color: #333333;
      font-size: .48rem;
      text-align: center;
    }
    .howWork_card_ri_reverse,
    .howWork_card_lf{
      .card_title{
        font-size: .42rem;
        font-family: Arial Black-Regular, Arial Black;
        font-weight: 400;
        color: #333333;
      }
      .card_subtitle{
        font-family: Work Sans-Regular, Work Sans;
        font-weight: 400;
        color: #7B7B7B;
        margin-bottom: .6rem;
      }
      .second_title_reverse{}
      .second_title{
        .second_title_icon{
          width: .2rem;
          height: .2rem;
          background-color: $blue1;
        }
        .second_title_icon_two{
          background-color: $black1;
        }
        .second_title_content{
          .second_title_content_main{
            font-family: Work Sans-SemiBold, Work Sans;
            font-weight: 600;
            color: #333333;
          }
          .second_title_content_sub{
            font-family: Work Sans-Regular, Work Sans;
            font-weight: 400;
            color: #7B7B7B;
          }

        }
      }

    }
    .howWork_card_lf_reverse,
    .howWork_card_ri{
      .howWork_card_img{
        width: 6.00rem;
        height: 4.50rem;
      }
    }
  }
  .works_that{
    width: 100%;
    background-color: rgba(249, 251, 254, 1);
    .works_that_title{
      font-size: .48rem;
      font-family: Arial Black-Regular, Arial Black;
      font-weight: 400;
      color: #333333;
      line-height: .59rem;
      text-align: center;
    }
    .works_that_card{
      .that_card{
        .that_card_foot{
          width: 2.3rem;
          font-size: .24rem;
          font-family: Arial Black-Regular, Arial Black;
          font-weight: 400;
          color: #7B7B7B;
          line-height: .3rem;
          text-align: center;
          word-wrap: break-word;
        }
      }
    }

  }
  .work_protect{
    background-color: rgba(249, 251, 254, 0);
    .that_card{
      background: #FFFFFF;
      box-shadow: 0 .01rem .1rem 0 rgba(0,0,0,0.1);
      border-radius: .1rem;
      .protect_card_foot{
        font-family: Work Sans-Bold, Work Sans;
        font-weight: bold;
        color: #333333;
      }
    }
  }
  .why_us{
    .why_us_title{
      color: #ffffff;
    }
    .that_card{
      .why_us_num{
        font-family: Work Sans-Bold, Work Sans;
        font-weight: bold;
        color: #205EFF;
      }
      .why_us_num_sutitle{
        font-family: Work Sans-Bold, Work Sans;
        font-weight: bold;
        color: #FFFFFF;
      }
      .why_us_num_title{
        font-family: Work Sans-Regular, Work Sans;
        font-weight: 400;
        color: rgba(255,255,255,0.6);
      }
    }
  }
}
</style>