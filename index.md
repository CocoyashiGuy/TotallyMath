## Welcome to the Greatest Game Website Ever

You can also go to [The All Purpose Website](https://sites.google.com/lpssonline.com/theallpurposewebsite/home) to play other games, some games may not work.



<!DOCTYPE html>
<html lang="en">

        <div id="middlebar">
            <p>Totally Science</p>
        </div>

        <div id="rightbar">
            <a id="login" href="profile.html">
                <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="currentColor" class="bi bi-person-fill" viewBox="0 0 16 16">
                    <path d="M3 14s-1 0-1-1 1-4 6-4 6 3 6 4-1 1-1 1H3zm5-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"/>
                </svg>
            </a>

            <a id="settings" href="preferences.html"><img src="./assets/images/settings-light.svg"></img>
            </a>
        </div>
    </div>

    <section id="browser">
        <div id="browserDiv" style="margin-top: 100px; margin-left: 50%; transform: translate(-50%); width: 90vw; height: 50vw; overflow-x: hidden;">
            <!--<p style="color: red; font-size: 50px; text-align: center;">Browser in maintanance...</p>-->
            <div style="width: 100%; height: 100%;">

                <iframe style="position: absolute; top: 0px; left: 0px; width: 200%; height: 700px; border-radius: 20px;" src="" frameBorder="0" id="game-iframe"></iframe>
            </div>
        </div>
    </section>

    <script>
        const frame = document.getElementById('game-iframe');
        let randomNum = Math.floor(Math.random() * 8) + 1;;
        frame.src = `https://replit.com/@YodaCode/fx-us-${randomNum}?lite=1&outputonly=1`
    </script>
</body>

</html>
