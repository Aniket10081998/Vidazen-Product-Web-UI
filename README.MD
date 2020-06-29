Common css which is used in all pages are "line.css" location :"css/line.css"
All images location:"css/image"
One different folder for green tick use in various page location:"css/code_successful_image/check.png"
All the css files are in css folder


1>Our first page is "index.html"
css :"line.css"
onclicking next -> "manually_entering_code.html" 


2>"manually_entering_code.html"
css:"manually_entering_code.css",
onclicking link "scan qr"->"scan_qr_code.html"
onclicking "pinkarrow"->"code_scanned_successfully.html"

3>"scan_qr_code.html" 
js:"app.js"
css:"line.css","scan_qr.css"

4>"code_scanned_successfully.html"
css:"line.css","verified.css"
waiting time of 5 sec ->"signup.html"

5>"signup.html"
You have to check the check box for terms and conditions then only the signup button will be enabled
css:"line.css","signup.css"
onclicking signup->"verify_account.html"

6>"verify_account.html"
css:"line.css","loading.css"
5 sec of wait ->"account_verified.html"

7>"account_verified.html"
css:"line.css","verified.css"
5 sec wait ->"connect_gateway.html"

8>"connect_gateway.html"
css:"line.css"
on clicking done ->"checking_connection.html"

9>"checking_connection.html"
css:"line.css","loading.css"
5 sec wait->"connection_established.html"

10>"connection_established.html"
css:"line.css","connection_established.css"
5 sec wait->"connection_successful.html"

11>"connection_successful.html"
css:"line.css","verified.css"
5 sec wait ->"avtar.html"

12>"avtar.html"
css:"avtar.html","line.css"
5 sec wait->"setup_site.html"

13>"setup_site.html"
css:"line.css","setup_site.css"
on click->"motion_sensor1.html"

14>"motion_sensor1.html"
css:"line.css","motion_sensor1.html"
onclick->"motion_sensor2.html"

14>"motion_sensor2.html"
css:"line.css","motion_sensor1.html"
onclick->"good_job.html"

15>"good_job.html"
css:"line.css","verified.css"
5 sec wait->"door_sensor.html"

16>"door_sensor.html"
css:"line.css","motion_sensor1.css","door_popup.css"
on click->"door_sensor_done.html"


HTML file not used:"gateway_not_found.html"
css:"line.css","gateway_not_found.css"