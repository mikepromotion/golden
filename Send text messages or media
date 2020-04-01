<?php

$curl = curl_init();

curl_setopt_array($curl, array(
  CURLOPT_URL => "https://panel.rapiwha.com/send_message.php?apikey=MY_API_KEY&number=7A8RDK8UX8TVUQF317S7&text=MyText",
  CURLOPT_RETURNTRANSFER => true,
  CURLOPT_ENCODING => "",
  CURLOPT_MAXREDIRS => 10,
  CURLOPT_TIMEOUT => 30,
  CURLOPT_HTTP_VERSION => CURL_HTTP_VERSION_1_1,
  CURLOPT_CUSTOMREQUEST => "GET",
));

$response = curl_exec($curl);
$err = curl_error($curl);

curl_close($curl);

if ($err) {
  echo "cURL Error #:" . $err;
} else {
  echo $response;
}
