<main>
    <div class="container">
            <div style="text-align:right;"></div>
                <div style="min-height:360px;">
                    <div class="container2">
                        <div id="check">Check your internet speed..</div>
                        <iframe id="x" src="//openspeedtest.com/speedtest" />
                        <div id="check3">
                            <input type="button" id="check2" value="Retry test" onclick="location.reload();">
                        </div>
                    </div>
                </div>
            </div>
</main>

<style>
    .container {
        display: inline-block;
        background: linear-gradient(
            45deg,
            rgb(0, 0, 194),
            rgba(255, 0, 85, 0.452)
        );
        border-radius: 20px;
        text-align: center;
        padding: 5vh;
        font-size: 30px;
        align-items: center;
        height: 70vh;
        width: 32ch;
        top: 45%;
        left: 50%;
        position: absolute;
        margin-top: -200px;
        margin-left: -250px;
    }
    .container2 {
        display: inline-block;
        background: linear-gradient(
            45deg,
            rgb(0, 0, 194),
            rgba(255, 0, 85, 0.452)
        );
        border-radius: 20px;
        text-align: center;
        padding: 5vh;
        font-size: 30px;
        align-items: center;
        color: #ffffff;
        height: 70vh;
        width: 32ch;
        top: 46%;
        left: 45%;
        position: absolute;
        margin-top: -200px;
        margin-left: -250px;
    }
    #x {
        border: none;
        margin-top: 9px;
        border-radius: 25px;
        width: 90%;
        height: 90%;
        border: none;
        background-color: transparent;
    }
    #check{
        border:bold black 1px;
        border-radius: 9px;
    }
    #check2{
        margin-top: 20px;
        border: 0px;
        padding-right: 3ch;
        padding-left: 3ch;
        border-radius: 15px;
        color: white;
        background: linear-gradient(
            45deg,
            rgb(0, 81, 255),rgb(212, 0, 255)
        );
        padding-top: 3px;
        padding-bottom: 3px;
        font-size: 27px;
    }
</style>
