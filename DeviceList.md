# IoT Kit Hands-on Training Ver 4 対応デバイス
IoT Kit Hands-on Training Ver 4の実習用デバイス一覧です。 
## Raspberry Pi3 + TI Sensor Tag CC2650 
[Azure IoT Edge SDK](http://github.com/Azure/iot-edge)を使って、Raspbianで実習します。  
→[説明資料](https://1drv.ms/p/s!Aihe6QsTtyqct5NNh7x8T_5g0zXQuw)  
※[東京エレクトロンデバイス株式会社 Azure IoT PoCキット1：Armadillo-IoTゲートウェイ G3](https://esg.teldevice.co.jp/azure-iot/iotportal/column_ex/detail/id/146/)でも実行可能

## Windows 10 IoT Core Device + TI Sensor Tag CC2650 
Windows 10 IoT Coreが動作するデバイスを使った実習です。 
→[説明資料](https://github.com/ms-iotkithol-jp/WinIoTCoreTIIoTHubApp) 

## Arduino + Sakura.io
Arduino＋[sakura.io モジュール](https://sakura.io/product/module_lte.html)を使った実習です。
→[説明資料](https://gist.github.com/Nyuuki0224/2d686b06eea235b88fd91681a638df3b#azure-part1)

## Device Emulator on Azure Functions 
Azure Functions上で動作するデバイスエミュレータです。 
→[リポジトリ](https://github.com/ms-iotkithol-jp/DeviceEmulatorOnFunctions)  

## Windows 10 IoT Core Device + SenseHat
Windows 10 IoT Coreが動作するRaspberry Pi3で、SenseHat装着したデバイスを使った実習です。
→[サンプルアプリと手順](https://github.com/ms-iotkithol-jp/WinIoTCoreSenseHATApp)

## STマイクロエレクトロニクス [NEUCLEO](http://www.st.com/content/st_com/en/products/evaluation-tools/solution-evaluation-tools/communication-and-connectivity-solution-eval-boards/p-nucleo-azure1.html) 
→[説明資料](http://www.st.com/content/st_com/en/products/embedded-software/mcus-embedded-software/stm32-embedded-software/stm32-ode-function-pack-sw/fp-cld-azure1.html)  
※第二章ステップ1のクエリーは、device-specific/Query-STMicro-NEUCLEO.txtを使う事 

## Azure IoT Edge SDK Ver 2 Emulator 
→[説明資料](https://docs.microsoft.com/ja-jp/azure/iot-edge/)  
※5分間のクイックスタート（WindowsまたはLinux）を実施→チュートリアルの「モジュールを展開する」まで実施  
※第二章ステップ1のクエリーは、device-specific/Query-IoTEdgeSDKV2-tempSensor.txtを使う事

## Seeed Wio LTE + SORACOM Beam
Seeed Wio LTEとSORACOM Beam - [Grove IoT Starter Kit](https://soracom.jp/products/kit/grovestarter_kit_3g_soracom_edition/) - を使って学習します。
→[説明資料](https://www.slideshare.net/SeeedJP/iot-kit-seeed-wio-lte-soracom-beam-v41)

## Raspbery Pi + SenseHat + SORACOM Beam
Raspberry PiとSenseHat、SORACOM Beamを使って学習します。
→[説明資料](https://github.com/ms-iotkithol-jp/RPi3SenseHatSORACOM)

## IoT Device Simulator  
MACやWindowsを使って学習します。  
→[開発サイト](https://github.com/ms-iotkithol-jp/IoTDeviceSamples)  
→[資料](https://1drv.ms/p/s!Aihe6QsTtyqct-IS-ARyuLG9mNwWyQ)

## NVIDIA JETSON TX2
[NVIDIA JETSON TX2](https://developer.nvidia.com/embedded/buy/jetson-tx2-devkit)上で動く、[IoT ALGYANから公開されているハンズオン](https://algyan.connpass.com/event/105282/)をカスタマイズして、Azure IoT Hubに接続 
→[資料](https://github.com/ms-iotkithol-jp/nvidia-jetson-tx2)

## Raspberry Pi + SenseHat + Webcam 
Raspberry PiとSenseHat、Webcamを使って、Custom Visionで学習させたモデルをIoT Edgeで動かし、認識結果とセンサー計測データをAzure IoT Hubに送信します。 
→[資料](https://github.com/ms-iotkithol-jp/Custom-vision-service-iot-edge-raspberry-pi/blob/master/Extended.md) 

# 求！Contributors 
実習コンテンツは、クラウド側とやり取りするデータ形式を合わせれば、[Azure IoT Device SDK](http://github.com/Azure/azure-iot-sdks)が動作する様々なデバイスで実習可能です。 
デバイスベンダー、センサーベンダー、及び、Geekの皆様、是非、得意なデバイスに関するコンテンツの作成協力よろしくお願いいたします。   
IoT Hubをはじめとする様々なPaaSは機能がどんどん増えていきます。また、Githubで公開されているリポジトリも偶に変わり、ここで公開しているテキストがうまく動かない状況も多々発生します。  
そんな時は、Issueに書くか、Pull&Requestしてくださいませー
