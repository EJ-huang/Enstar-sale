<template>
    <div class="main h-100 bg-dark_black  text-2xl mt-12 pt-12">
        <div class="box flex  bg-secondary text-2xl text-white mt-5 py-1  mx-5 my-5  rounded-md p-4">
            <img src="../assets/star1.png" alt="">
            <h1 class="flex content-center mt-12">IMPORTANT</h1>
        </div>
        <ol class="list-disc p-10 text-left font-black text-secondary">
            <li>短線交易的秘密公式</li>
            <span> 將幫助你建立清晰有架構的交易方式，並讓你有信心在股市中達成穩定獲利 !</span>
            <li>短線交易的秘密公式</li>
            <span> 你可以清楚了解到「交易公式」的威力，並實際應用在不同的金融商品 !</span>
            <li>短線交易的秘密公式</li>
            <span> 將帶領你，運用小資金操作股市，逐步滾起百萬獲利！</span>
        </ol>
    <div class="main text-left p-2 leading-10">
        <h1 class="font-bold text-2xl text-white">這套短線交易公式已被應用於</h1>
    </div>
        <hr class="mt-2 py-4">
        <div class="main2">
            <div class="box flex text-secondary">
                <h1>01</h1>
                <span>台股股票</span>
            </div>  
            <div class="content flex p-2">
                <div class="content-1 text-xl  flex flex-col pl-2">
                    <p>尋找飆股學生曾抓出近<span>300%獲利飆股 !</span></p>
                    <img src="../assets/form1.png" alt="">
                </div>
                <img src="../assets/form.png" alt="">
                <!-- <div class="content-2 pr-2">
                    <img src="../assets/foot.png" alt="">
                </div> -->
            </div>         
        </div>
        <div class="main2">
            <div class="box flex text-secondary">
                <h1>02</h1>
                <span>台股台指期當沖</span>
            </div>  
            <div class="content flex pt-8">
                <div class="content-1 text-xl  flex pl-2">
                    <p>分析盤勢，清楚抓出近期走向，台股一次下殺，<span>獲利達1000點！</span></p>
                    <img src="../assets/form2.png" alt="">
                </div>
            </div>         
        </div>
        <div class="main2">
            <div class="box flex text-secondary">
                <h1>03</h1>
                <span>台股台指期波段</span>
            </div>  
            <div class="content flex pt-8">
                <div class="content-1 text-xl  flex pl-2">
                    <p>當你短線交易做的成功了，來挑戰波段單，獲利更驚人</p>
                </div>
            </div>         
        </div>
        <div class="main2">
            <div class="box flex text-secondary">
                <h1>04</h1>
                <span>美股當沖</span>
            </div>  
            <div class="content flex pt-8">
                <div class="content-1 text-xl  flex pl-2">
                    <p>當初這套公式，就是在美股當沖中練成，自然能應用到美股上！</p>
                </div>
            </div>         
        </div>
        <div class="main2">
            <div class="box flex text-secondary">
                <h1>05</h1>
                <span>美股個股交易</span>
            </div>  
            <div class="content flex pt-8">
                <div class="content-1 text-xl  flex pl-2">
                    <p>有在關注特斯拉？蘋果？想交易美股，也可以透過公式解析！</p>
                </div>
            </div>         
        </div>
    <div class="box1 p-4">
        <div class="flex side-box justify-center bg-black text-2xl text-white mt-12  py-1 px-2  mx-5 my-5 rounded-md p-5">
            <img src="../assets/star2.png" alt="">
            <h1 class="flex content-center pt-2">限額!名額有限!</h1>
        </div>
        
        <p class="text-white">短線交易的秘密公式</p>
        <p class="text-white"> 開始規劃出明確走勢</p>
        <p class="text-secondary">用三萬小資金，創造百萬獲利!</p>

        <button class="bg-secondary hover:bg-blue-700 text-white font-bold py-2 px-12  rounded mt-8">
        / 搶佔免費講座席次
        </button>
    </div>
  </div>
  
</template>


<style lang="scss" scoped>

    .main{
        .box{
            position: relative;
            img{
                width: 150px;
                padding-right: 10px;
            }
        }
        ol{
            span{
                font-size: 16px;
                color: #fff;
            }
        }
    }
    .main2{
        .box{
            width: 20rem;
            background: #1E252C;
            border-radius: 0 10px 10px 0;

        }
        h1{
            font-size: 48px;
            font-weight: 700;
        }
        .content{
            img{
                width: 10rem;
            }
            p{
                color: #fff;
            }
            span{
                color: #46AFB0;
            }
        }
    }
.box1{
    background-image: url('../assets/foot2.png');
    background-size: cover;
    height: 50vh;
    width: 100%;
    background-repeat: no-repeat;
    padding: 10px;

    .side-box{
        img{
            width: 6rem;
            padding: 10px;
        }
    }
}

</style>