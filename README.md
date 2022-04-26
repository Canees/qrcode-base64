# qrcode-base64

基于 base64 编码输出二维码

## 代码参考 Pudon/weapp-qrcode-base64 结合 delenzhang 的 pr

### exp:

    const QR = require('./utils/qrcode_base64')
    const base64 = QR.drawImg(content, {
      version: 1, //最大40
      errorCorrectLevel: 'M',
      color: '#3d0d83', //支持rgb
      background: '#fff',//支持rgb
      padding: 1,
      size: 200 //请用正整数
    })
