
 <style> html { height: 100%; }
    body {
        background-image: url("https://icrvb3jy.xinmedia.com/solomo/article/12505/5DCD1BA6-945E-42BA-BD02-54BA768780B6.jpg");
        background-repeat: no-repeat;
        background-attachment: fixed;
        background-position: center;
        background-size: cover;
    }
    
    p {
        font-size: 18px;
        font-family: Microsoft JhengHei;
    }
    
    h2 {
        font-family: "微軟正黑體";
        font-weight: bold;
    }
    
    td {
        font-family: "微軟正黑體";
        font-size: 18px;
    }
    /* button*/
    .button {
        background-color: #a0fdff;
        border: 2px solid black;
        color:  #0645ad;
        padding: 8px 24px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        display: block;
    }
    
    .button:hover {
        background-color: #A1D0FF;
    }
    
    #flip {
        background-color: #a0fdff;
        border: 2px solid black;
        color: black;
        padding: 8px 42px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
        display: block;
    }
    
    .button-bar {
        position: fixed;
        top: 5%;
        right: 5%;
    }
    
    
    
    
    /*light box*/
    
     * {
        box-sizing: border-box
    }
    
    body {
        font-family: Verdana, sans-serif;
        margin: 0
    }
    
    .mySlides {
        display: none
    }
    
    img {
        vertical-align: middle;
    }
    /* Slideshow container */
    
    .slideshow-container {
        max-width: 1000px;
        position: relative;
        margin: auto;
    }
    /* Next & previous buttons */
    
    .prev,
    .next {
        cursor: pointer;
        position: absolute;
        top: 50%;
        width: auto;
        padding: 16px;
        margin-top: -22px;
        color: white;
        font-weight: bold;
        font-size: 18px;
        transition: 0.6s ease;
        border-radius: 0 3px 3px 0;
        user-select: none;
    }
    /* Position the "next button" to the right */
    
    .next {
        right: 0;
        border-radius: 3px 0 0 3px;
    }
    /* On hover, add a black background color with a little bit see-through */
    
    .prev:hover,
    .next:hover {
        background-color: rgba(0, 0, 0, 0.8);
    }
    /* Caption text */
    
    .text {
        color: #f2f2f2;
        font-size: 15px;
        padding: 8px 12px;
        position: absolute;
        bottom: 8px;
        width: 100%;
        text-align: center;
    }
    /* Number text (1/3 etc) */
    
    .numbertext {
        color: #f2f2f2;
        font-size: 12px;
        padding: 8px 12px;
        position: absolute;
        top: 0;
    }
    /* The dots/bullets/indicators */
    
    .dot {
        cursor: pointer;
        height: 15px;
        width: 15px;
        margin: 0 2px;
        background-color: #bbb;
        border-radius: 50%;
        display: inline-block;
        transition: background-color 0.6s ease;
    }
    
    .active,
    .dot:hover {
        background-color: #717171;
    }
    /* Fading animation */
    
    .fade {
        -webkit-animation-name: fade;
        -webkit-animation-duration: 1.5s;
        animation-name: fade;
        animation-duration: 1.5s;
    }
    
    @-webkit-keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    
    @keyframes fade {
        from {
            opacity: .4
        }
        to {
            opacity: 1
        }
    }
    /* On smaller screens, decrease text size */
    @media only screen and (max-width: 300px) {
        .prev,
        .next,
        .text {
            font-size: 11px
        }
    }
    
    
    
    
    /*tabs*/
     body {
        font-family: Arial;
    }
    /* Style the tab */
    
    .tab {
        overflow: hidden;
        border: 1px solid #ccc;
        background-color: #f1f1f1;
    }
    /* Style the buttons inside the tab */
    
    .tab button {
        background-color: inherit;
        float: left;
        border: none;
        outline: none;
        cursor: pointer;
        padding: 10px 12px;
        transition: 0.3s;
        font-size: 17px;
    }
    /* Change background color of buttons on hover */
    
    .tab button:hover {
        background-color: #ddd;
    }
    /* Create an active/current tablink class */
    
    .tab button.active {
        background-color: #ccc;
    }
    /* Style the tab content */
    
    .tabcontent {
        display: none;
        padding: 6px 12px;
        border: 1px solid #ccc;
        border-top: none;
    }
    
    
    /*video*/
    .video-container {
    position: relative;
    padding-bottom: 56.25%;
    padding-top: 30px;
    height: 0;
    overflow: hidden;
    }

    .video-container iframe,
    .video-container object,
    .video-container embed {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    }

   
</style>

<head>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.0/jquery.min.js"></script>
    <script>
        $(document).ready(function() {
            $('#top').click(function() {
                $('html, body').animate({
                    scrollTop: 0
                }, 1000);
            });
            $('#bottom').click(function() {
                $('html, body').animate({
                    scrollTop: $(document).height() - $(window).height()
                }, 1000);
            });
            $('#a').click(function() {
                $('html, body').animate({
                    scrollTop: $("#A").offset().top
                }, 1000);
            });
            $('#b').click(function() {
                $('html, body').animate({
                    scrollTop: $("#B").offset().top
                }, 1000);
            });
            $('#c').click(function() {
                $('html, body').animate({
                    scrollTop: $("#C").offset().top
                }, 1000);
            });
            $('#d').click(function() {
                $('html, body').animate({
                    scrollTop: $("#D").offset().top
                }, 1000);
            });
            $('#e').click(function() {
                $('html, body').animate({
                    scrollTop: $("#E").offset().top
                }, 1000);
            });
            $('#f').click(function() {
                $('html, body').animate({
                    scrollTop: $("#F").offset().top
                }, 1000);
            });
            $("#flip").click(function() {
                $(".button").slideToggle("slow");
            });
        });
    </script>
</head>
<div id="google_translate_element"></div>

<script type="text/javascript">
function googleTranslateElementInit() {
  new google.translate.TranslateElement({pageLanguage: 'zh-tw', layout: google.translate.TranslateElement.InlineLayout.SIMPLE}, 'google_translate_element');
}
</script>

<script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
<center><h1 style="font-size:40px;font-weight:bold;">澎湖南方四島國家公園</h1></center>

<h2 class="header-level-2" id="A">基本資訊:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <ol>
        <li>
            <p>澎湖南方四島國家公園為中華民國內政部營建署海洋國家公園管理處自2010年開始籌設的國家公園，於2014年6月8日正式公告實施，並於10月18日掛牌。「澎湖南方四島國家公園」是臺灣第九座國家公園，也是第二座海洋型國家公園。澎湖南方四島是由東吉嶼、西吉嶼、東嶼坪嶼、西嶼坪嶼，這四個較大島嶼及周圍小型島嶼與海域組成，生態資源珍貴且物種多樣性高，海域珊瑚礁生長茂密，亦為適合浮潛的地點。 範圍以「澎湖縣」的「東吉嶼」、「西吉嶼」、「東嶼坪嶼」、「西嶼坪嶼」等四島及周邊島礁與海域，分別以東吉嶼向東、頭巾向北及向西與鐘仔向南各2浬為邊界，依北緯23°12'4.55"—23°19'28.76"與東經119°27'51.09"—119°43'4.23"之範圍內劃設為帶狀區域，海域面積35,473.33公頃，陸域面積370.29公頃，全區面積35,843.62公頃[4]。其中部分陸域範圍已於2008年公告為澎湖南海玄武岩自然保留區。</p>
        </li>
        
    </ol>
</div>

<h2 class="header-level-2" id="B">國家公園標示意涵:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <img align="left" style="width: 100px; height: 100px;" src="https://i2.wp.com/fengtaiwanway.com/wp-content/uploads/2018/05/penghutravel4_3_006-1.jpg?resize=800%2C533&ssl=1">
    <center>
        <p>澎湖南方四島國家公園的標誌是使用海洋國家公園管理處的標誌,海洋國家公園管理處徵以海洋國家公園管理處英文名稱M為設計元素,運用流暢飄逸之書法筆觸表現海浪波動,象徵海洋元素生命力旺盛,及搭配深淺藍與白色視覺效果,融合於水墨自由暈開之圖形,呈現海洋資源豐沛之意象
        </p>
    </center>
</div>

<h2 class="header-level-2" id="C">特色介紹:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">

<p></p>
    <body>

<div class="tab">
    <button class="tablinks" onclick="openCity(event, '東嶼坪')" id="defaultOpen">東嶼坪</button>
    <button class="tablinks" onclick="openCity(event, '東吉嶼')">東吉嶼</button>
    <button class="tablinks" onclick="openCity(event, '西嶼坪')">西嶼坪</button>
    <button class="tablinks" onclick="openCity(event, '西吉嶼')">西吉嶼</button>
  <button class="tablinks" onclick="openCity(event, ' 附屬島嶼')"> 附屬島嶼</button>
   
   
    <button class="tablinks" onclick="openCity(event, '相關影音')">相關影音</button>
</div>

<div id="東嶼坪" class="tabcontent">
    <h2>東嶼坪</h2>
    <p>

東嶼坪上有東嶼坪安檢所、衛生室、派出所、南方四島國家公園等公家單位，島上的公務人員比居民還多。從高處望下的東嶼坪梯型田地與港灣，是來到當地的必攝景點，高處望下更可看見鄰島的西嶼坪。。</p>
   
</div>

<div id="東吉嶼" class="tabcontent">
    
    <h2>東吉嶼</h2>
    <p> 

東吉嶼距離臺南近，居民大多移居臺灣南部，目前長期定居的人口只約2位數。東吉燈塔是東吉的地標，登上山頭，俯瞰島上平原地形、東吉港口海灣、清澈海水、美麗沙灘、妝點其中的民宅，東吉的純樸自然，令人終生難忘。。</p>
   
</div>

<div id="西嶼坪" class="tabcontent">
    <h2> 西嶼坪</h2>
    <p>

西嶼坪的長住人口僅有個位數，屬望安鄉公所管轄。西嶼坪的周邊海域是浮潛勝地，周邊海域珊瑚礁覆蓋率高，每年皆吸引熱愛潛水的遊客前往觀賞海底風光。</p>
  
</div>

 <div id="西吉嶼" class="tabcontent">
    <h2>西吉嶼</h2>
    <p>

西吉嶼是南方四島當中海拔最平坦的島嶼。東北岸有延綿數百公尺的柱狀玄武岩海崖，節理分明，與碧藍海水輝映著。西吉嶼的村內，也因遷村三十餘年，島內荒煙蔓草，偶可見人文智慧的菜宅隱隱守著這片孤島。島嶼北側的灶籠是近期很受遊客青睞的藍洞。</p>
</div>

 <div id=" 附屬島嶼" class="tabcontent">
    <h2> 頭巾</h2>
    <p>由北方海面遠望，這座小島的形狀有如古人的頭巾一般故得此名。島上可見傾斜覆蓋在火山角礫岩上的玄武岩岩脈、受海潮侵蝕分離的海蝕柱，以及鑽蝕作用形成的壺穴等豐富地質景觀，目前已劃入澎湖南海玄武岩自然保留區。四立的岩礁與海潮帶來的漁獲，使頭巾於夏季時成為燕鷗繁殖棲息的天堂。</p>
   <h2> 鐵砧</h2>
    <p>從海上可見具有一大一小的海蝕柱，較大的海蝕柱可清楚看到傾斜狀的層理；由某一角度觀看，形似女子頭部，故有女王頭之稱；春夏之季是燕鷗候鳥棲息與繁殖的場所，在岩壁上可發現許多燕鷗候鳥所留下的蹤跡，巡航經過時常可發現成群的候鳥在島附近飛舞，是觀鳥景點之一。</p>
   <h2> 鐘仔</h2>
    <p>外形相似早期懸鐘形，其漲潮時其延伸出的低平礁岩會隱沒在水中，退潮時可完全顯現。主體高聳的鐘仔與豬母礁座落同一海域，漁產豐富常吸引多種之燕鷗鳥類駐足，春夏之際也是候鳥過境的基地之一。</p>
   <h2> 豬母礁</h2>
    <p>平常隱沒海中，退潮時方浮出海面，為了往來船隻安全，上方設有小型自動明滅燈塔一座。 其周圍海域漁產豐富，巡航時常可觀察到多種燕鷗（夏候鳥）、岩鷺（留鳥）在此停棲活動。</p>
   <h2> 二塭</h2>
    <p>由火山集塊岩組成，其兩側延伸出的礁石退潮時將隱沒於海面下，遠望形如尖錐狀。</p>
  <h2> 香爐</h2>
    <p>香爐由火山角礫岩構成，其位於東嶼坪嶼東南方，因形狀似香爐而得名，從東嶼坪嶼的南方陸塊頂端及南側沙灘皆可遠觀欣賞。</p>
  <h2> 鋤頭嶼</h2>
    <p>柱狀玄武岩及火山角礫岩所組成，島周圍海岸皆為壯麗的海崖及受到強勁海流侵襲形成海蝕洞景觀，北側的海蝕平台，冬季盛產紫菜是鋤頭嶼重要的生態資源。
</p>
  <h2> 柴垵塭</h2>
    <p>面積僅有0.11公頃，為西吉嶼北方由火山碎屑岩構成的小岩礁，常見島上有燕鷗棲息。</p>
    <h2> 離塭仔</h2>
    <p>
　離塭仔(南塭仔、蜈蚣仔)位於東嶼坪嶼西南方，面積僅有0.25公頃，主要由火山碎屑岩所構成，其地勢平坦，最高點約2.8公尺。</p>
</div>



<div id="相關影音" class="tabcontent">
<div class="video-container">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/b0MUUxmLy1I" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    </div>





<script>
    function openCity(evt, cityName) {
        var i, tabcontent, tablinks;
        tabcontent = document.getElementsByClassName("tabcontent");
        for (i = 0; i < tabcontent.length; i++) {
            tabcontent[i].style.display = "none";
        }
        tablinks = document.getElementsByClassName("tablinks");
        for (i = 0; i < tablinks.length; i++) {
            tablinks[i].className = tablinks[i].className.replace(" active", "");
        }
        document.getElementById(cityName).style.display = "block";
        evt.currentTarget.className += " active";
    }

    // Get the element with id="defaultOpen" and click on it
    document.getElementById("defaultOpen").click();
</script>
   </body>
    <p></p>
        <div class="slideshow-container">

    <div class="mySlides fade">
        <div class="numbertext">1 / 5</div>
        <img style="width:100%;height:400px" src="https://images.chinatimes.com/newsphoto/2014-10-18/900/20141018002972.jpg">
        <div class="text"> 藍洞</div>
    </div>

    <div class="mySlides fade">
        <div class="numbertext">2 / 5</div>
        <img style="width:100%;height:400px" src="https://www.penghu-nsa.gov.tw/FileDownload/Scenery/Big/20160907103937579129421.jpg" >
        <div class="text"> 雙心石滬</div>
    </div>

    <div class="mySlides fade">
        <div class="numbertext">3 / 5</div>
        <img style="width:100%;height:400px" src="https://www.marine.gov.tw/filesys/image/01_chinese/newimages/0403/0403_01-03_a_04.jpg">
        <div class="text"> 東吉燈塔</div>
    </div>
    
    <div class="mySlides fade">
        <div class="numbertext">4 / 5</div>
        <img style="width:100%;height:400px" src="https://www.marine.gov.tw/filesys/image/01_chinese/newimages/0403/0403_01-03_a_08.jpg">
        <div class="text"> 海蝕平台  </div>
    </div>
    
    <div class="mySlides fade">
        <div class="numbertext">5 / 5</div>
        <img style="width:100%;height:400px" src="https://www.marine.gov.tw/filesys/image/01_chinese/newimages/0403/0403_01-03_a_06.jpg">
        <div class="text"> 菜宅</div>
    </div>
    
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
    <span class="dot" onclick="currentSlide(4)"></span>
    <span class="dot" onclick="currentSlide(5)"></span>
</div>

<script>
    var slideIndex = 1;
    showSlides(slideIndex);

    function plusSlides(n) {
        showSlides(slideIndex += n);
    }

    function currentSlide(n) {
        showSlides(slideIndex = n);
    }

    function showSlides(n) {
        var i;
        var slides = document.getElementsByClassName("mySlides");
        var dots = document.getElementsByClassName("dot");
        if (n > slides.length) {
            slideIndex = 1
        }
        if (n < 1) {
            slideIndex = slides.length
        }
        for (i = 0; i < slides.length; i++) {
            slides[i].style.display = "none";
        }
        for (i = 0; i < dots.length; i++) {
            dots[i].className = dots[i].className.replace(" active", "");
        }
        slides[slideIndex - 1].style.display = "block";
        dots[slideIndex - 1].className += " active";
    }
</script>
    
    
    
    <p></p>


</div>

<h2 class="header-level-2" id="D">交通資訊:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
 <body>
<div class="tab">
    <button class="tablinks" onclick="openCity(event, '聯外交通')">聯外交通</button>
    <button class="tablinks" onclick="openCity(event, '島上交通')">島上交通</button>
 

</div>

<div id="聯外交通" class="tabcontent">
    <h2 style="color:#FF8800;font-weight:bold;">聯外交通:</h2>
   
<p>
   澎湖南方四島目前對外交通以海運為主，除西吉嶼無建設碼頭外，其餘東嶼坪嶼及東吉嶼設有漁港（第二類漁港），另西嶼坪嶼則設置有簡易突堤碼頭，主要提供離島或偏遠地區的作業漁船臨時停泊或避風使用。<br>
　　海運又可分為包船直接抵達及轉乘抵達：<br>
1.	海運直接抵達<br>
 	從臺南出發至東吉嶼約2.5小時航程，目前有民營客輪固定開航，東嶼坪嶼及西嶼坪嶼目前尚無固定交通船前往。<br>
2.	海運轉乘海運<br>
 	須由澎湖縣馬公搭乘南海交通船至望安，再由望安島包船前往各島或搭乘不定期交通船前往。<br>
3.	空運轉乘海運<br>
 	由臺灣本島搭乘飛機至馬公或直接至望安（至馬公者須再轉海運至望安島），再由望安島包船前往各島或搭乘不定期交通船前往。<br>
以上海空運資訊可洽:澎湖南海遊客中心 (06)9264738、澎湖縣望安鄉公所 (06)9991311、澎湖南海交通船馬公售票處站 (06)9213822#102、103<br>
    </p>
</div>

<div id="島上交通" class="tabcontent">
    <h2 style="color:#FF8800;font-weight:bold;">島上交通:</h2>
    <p>
        東吉嶼、東嶼坪嶼及西嶼坪嶼三島均已開闢道路，步行即可前往島上各主要地區。
    </p>
</div>







<script>
    function openCity(evt, cityName) {
        var i, tabcontent, tablinks;
        tabcontent = document.getElementsByClassName("tabcontent");
        for (i = 0; i < tabcontent.length; i++) {
            tabcontent[i].style.display = "none";
        }
        tablinks = document.getElementsByClassName("tablinks");
        for (i = 0; i < tablinks.length; i++) {
            tablinks[i].className = tablinks[i].className.replace(" active", "");
        }
        document.getElementById(cityName).style.display = "block";
        evt.currentTarget.className += " active";
    }

    // Get the element with id="defaultOpen1" and click on it
    document.getElementById("defaultOpen1").click();
</script>
 </body>
</div>


<h2 class="header-level-2" id="E">住宿資訊:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <p>
        <table border="1" cellpadding="5" cellspacing="0" width="90%">
            <thead>
                <tr>
                    <th width="45%">民宿/飯店 </th>
                    <th width="48%">地址 </th>
                    
                    <th width="24%">網址 </th>
                </tr>
            </thead>
            <tbody>

                <tr>
                    <td>藍海風晴</td>
                    <td>澎湖縣馬公市山水里17之21號</td>
                    
                    <td><a href="https://www.summer-blue.com/Home.aspx/About">https://www.summer-blue.com/Home.aspx/About</a></td>
                </tr>

                <tr>
                    <td>藍海天晴</td>
                    <td>澎湖縣馬公市山水里48之6號</td>
                    
                     <td><a href="https://www.skysunnybnb.com/">https://www.skysunnybnb.com/</a></td>
                </tr>

                <tr>
                    <td>澎湖衫之林民宿</td>
                    <td>澎湖縣馬公市鎖港里1246號</td>
                    
                     <td><a href="http://www.lovinghut.com/portal/tw/bbs/board.php?bo_table=restaurants_tw&wr_id=48">http://www.lovinghut.com/portal/tw/bbs/board.php?bo_table=restaurants_tw&wr_id=48</a></td>
                </tr>

                <tr>
                    <td>澎湖福朋喜來登酒店</td>
                    <td>澎湖縣馬公市新店路197號</td>
                    
                     <td><a href="https://www.marriott.com/hotels/travel/mzgfp-four-points-penghu/?scid=bb1a189a-fec3-4d19-a255-54ba596febe2">https://www.marriott.com/hotels/travel/mzgfp-four-points-penghu/?scid=bb1a189a-fec3-4d19-a255-54ba596febe2</a>h</td>
                </tr>

                <tr>
                    <td>澎舢100民宿</td>
                    <td>澎湖縣馬公市線道201號</td>
                    
                     <td><a href="https://website--782920607661804303971-hotel.business.site/">https://website--782920607661804303971-hotel.business.site/</a></td>
                </tr>
            </tbody>
        </table>
    </p>
</div>

<h2 class="header-level-2" id="F">美食資訊:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <p>
        <table border="1" cellpadding="5" cellspacing="0" width="90%">
            <thead>
                <tr>
                    <th width="31%">店名</th>
                    <th width="43%">地址 </th>
                    <th width="23%">聯絡電話 </th>
                    <th width="23%">營業時間 </th>
                </tr>
            </thead>
            <tbody>

                <tr>
                    <td>案山乾麵店</td>
                    <td>澎湖縣馬公市經國路153號</td>
                    <td>無</td>
                    <td>上午6:00 – 下午1:30</td>
                </tr>

                <tr>
                    <td>鄉滋味小吃</td>
                    <td>澎湖縣七美鄉南港村4鄰25號</td>
                    <td>0928-370871</td>
                    <td>08:30～20:30</td>
                </tr>

                <tr>
                    <td>二崁一家仙人掌汁</td>
                    <td>澎湖縣西嶼鄉二崁村1號(陳家古厝)</td>
                    <td>(06)9982-165</td>
                    <td>09:00~18:00</td>
                </tr>

                <tr>
                    <td>歐萊壽司</td>
                    <td>澎湖縣馬公市文康街56號</td>
                    <td>(02)2861-1777</td>
                    <td>17:00–9:00</td>
                </tr>

                <tr>
                    <td>易家仙掌冰品 </td>
                    <td>澎湖縣白沙鄉191-2號</td>
                    <td>06 993 2297</td>
                    <td>8:30–18:00</td>
                </tr>
            </tbody>
        </table>
    </p>
</div>

<h2 class="header-level-2">資料來源:</h2>
<div style="background-color:#EEFFBB;border:2px black solid;padding:10px;">
    <ul>
        <li><a href="http://np.cpami.gov.tw/">台灣國家公園</a></li>
        <br>
        <li><a href="https://www.marine.gov.tw/%E6%9C%8D%E5%8B%99%E9%81%B8%E5%96%AE/%E5%85%A8%E6%96%87%E6%AA%A2%E7%B4%A2?searchword=%E6%BE%8E%E6%B9%96%E5%8D%97%E6%96%B9%E5%9B%9B%E5%B3%B6%E5%9C%8B%E5%AE%B6%E5%85%AC%E5%9C%92&searchword2=&ordering=0&logic=0&gc1=0&gc2=0&gc3=0">海洋國家公園管理處</a></li>
        <br>
        
        <li><a href="https://fengtaiwanway.com/penghutravel4_3/">澎湖四天三夜深度旅行第三天行程懶人包【澎湖旅遊】|在地仔領路玩法，南方四島國家公園及海上遊程就是要你讚嘆滿滿!!!</a></li>
        <br>
        <li><a href="https://www.trivago.com.tw/?themeId=457&iGeoDistanceItem=2512484&sem_keyword=%E9%99%BD%E6%98%8E%E5%B1%B1%20%E4%BD%8F%E5%AE%BF%20%E6%8E%A8%E8%96%A6&sem_creativeid=333376697745&sem_matchtype=e&sem_network=g&sem_device=c&sem_placement=&sem_target=&sem_adposition=1t1&sem_param1=&sem_param2=&sem_campaignid=1682128211&sem_adgroupid=71121431928&sem_targetid=kwd-635820411482&sem_location=1012825&cip=8861901253&gclid=EAIaIQobChMI3dPGgaKi4gIVGq6WCh2bkwmiEAAYASAAEgK6oPD_BwE">trivago</a></li>
        <br>
        <li><a href="https://zh.wikipedia.org/wiki/%E6%BE%8E%E6%B9%96%E5%8D%97%E6%96%B9%E5%9B%9B%E5%B3%B6%E5%9C%8B%E5%AE%B6%E5%85%AC%E5%9C%92">維基百科</a></li>
    </ul>
</div>

<div class="button-bar">
    <a id="flip">選單</a>
    <a class="button" id="a" href="#">基本資訊</a>
    <a class="button" id="b" href="#">標示意涵</a>
    <a class="button" id="c" href="#">特色介紹</a>
    <a class="button" id="d" href="#">交通資訊</a>
    <a class="button" id="e" href="#">住宿資訊</a>
    <a class="button" id="f" href="#">美食資訊</a>
    <a class="button" id="top" href="#">網頁頂端</a>
    <a class="button" id="bottom" href="#">網頁底部</a>
    <a class="button" id="home" href="https://jim99224.github.io/HomePage/">返回主頁</a>
</div>
 

