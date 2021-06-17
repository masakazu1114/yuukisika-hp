<template>
    <div class="body">
        <div class="header">
            <div class="header-logo">友紀歯科</div>
            <div class="header-list">
                <ul>
                    <li>施設情報</li>
                    <li>診療受付・休診日</li>
                    <li>アクセス</li>
                </ul>
            </div>
        </div>

        <div class="main">
            <div class="contents">
                <h1 class="section-title">施設情報</h1>
                <img src="https://pic1.homemate-research.com/pubuser1/pubuser_facility_img/5/0/0/24212300005/0000003195/24212300005_0000003195_1.jpg" alt="外観" class="picture">
                <table class="info">
                    <tr>
                        <th class="table-head">施設名</th>
                        <td class="table-data">友紀歯科医院</td>
                    </tr>
                    <tr>
                        <th class="table-head">診療科目</th>
                        <td class="table-data">歯科</td>
                    </tr>
                    <tr>
                        <th class="table-head">電話番号</th>
                        <td class="table-data">０５９７－８９－４６１８</td>
                    </tr>
                    <tr>
                        <th class="table-head">所在地</th>
                        <td class="table-data">〒５１９－４３２４　三重県熊野市井戸町７３５－２</td>
                    </tr>
                </table>
            </div>

            <div class="contents">
                <h1 class="section-title">診療受付・休診日</h1>
                <table class="tabletime">
                    <tr>
                        <th class="tabletime-head">時間</th>
                        <th class="tabletime-head">月</th>
                        <th class="tabletime-head">火</th>
                        <th class="tabletime-head">水</th>
                        <th class="tabletime-head">木</th>
                        <th class="tabletime-head">金</th>
                        <th class="tabletime-head">土</th>
                        <th class="tabletime-head">日</th>
                        <th class="tabletime-head">祝</th>
                    </tr>
                    <tr>
                        <td class="tabletime-data">9:00~12:00</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                    </tr>
                    <tr>
                        <td class="tabletime-data">14:00~18:00</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                    </tr>
                    <tr>
                        <td class="tabletime-data">14:30~19:30</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                    </tr>
                    <tr>
                        <td class="tabletime-info" colspan="9">
                            予約制・臨時休診あり
                        </td>
                    </tr>
                </table>
                <p class="coment">※新型コロナウイルス感染拡大により、診療時間・休診日等が記載と異なる場合がございますのでご注意下さい。</p>
            </div>

            <div class="contents">
                <h1 class="section-title">アクセス</h1>
                <table class="access">
                    <tr>
                        <th>交通手段</th>
                        <td>JR紀勢本線　熊野市駅より<span>徒歩5分</span></td>
                    </tr>
                </table>
                <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d13247.89172078296!2d136.097334!3d33.890351!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xff1ab8702fb2b0c7!2z5Y-L57SA5q2v56eR5Yy76Zmi!5e0!3m2!1sja!2sjp!4v1623326619736!5m2!1sja!2sjp" 
                width="300" 
                class="map"
                height="200" 
                style="border:0;" 
                allowfullscreen="" 
                loading="lazy"></iframe>
            </div>
        </div>
        <div class="footer">
            <div class="footer-list">ご予約・お問い合わせ</div>
            <div class="number">0597-89-4618</div>
        </div>
    </div>
</template>

<script>
export default {}
</script>

<style>
.header {
    background-color: skyblue;
    height: 90px;
    width: 1000px;
    color: snow;
}

.header-logo {
    font-size: 40px;
    float:left;
    padding: 20px 40px;
}

.header-list li {
    list-style: none;
    float: left;
    padding: 33px 20px;
}

.main {
    height: 1250px  ;
    width: 1000px;
}

.section-title {
    color:black;
    padding: 15px 40px;
    border-bottom: 2px dashed black;
    font-size: 30px;
}

.picture {
    height: 300px;
    width: 350px;
    float: right;
    padding: 25px 110px 30px 0px;
}

.info  {
    padding: 40px 50px 30px 50px;
    color:black;
}

.tabletime {
    padding: 40px 50px 30px 60px;
    color:black;
    text-align:center;
}

.access {
    padding: 40px 50px 0px 50px;
    color:black;
}

.access tr {
        text-align:center;
}

table th {
    padding-bottom: 10px;
    padding-right: 18px;
    font-size: 20px;
}

.coment {
    color: red;
    padding-bottom:20px;
    padding-left:60px;
}

.map {
    height: 300px;
    width: 850px;
    padding: 20px 110px 40px 50px;
}

.tabletime-head {
    padding: 10px 20px;
    border: solid 3px;
}

.tabletime-data {
    padding: 10px 20px;
    border: solid 3px;
}

.tabletime-info {
    text-align: center;
    padding: 10px 0px;
    border: solid 3px;
}

span {
    font-size: 20px;
}

.footer {
    background-color: skyblue;
    width: 1000px;
    height: 100px;
}

.footer-list {
    padding: 25px 40px 0px 40px;
    color: white;
}

.number {
    padding: 5px 40px;
    color: white;
}
</style>

