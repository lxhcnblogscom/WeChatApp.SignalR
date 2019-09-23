# WeChatApp.SignalR
适用于 微信小程序的SignalR (SignalRCore)

目前该项目支持一下 Transport / Follow Transports are supported right now
- [x] WeChatWebSocketTransport
    - [x] JsonProtocal
        - [x] TextFormate
        - [ ] Binary （not test yet）
- [ ] ~~ServerSentEventTransport~~ Does it possible to use SSE on wechat miniprogram
    - [ ] JsonProtocal
        - [ ] TextFormate
        - [ ] Binary （not test yet）
- [ ] WeChatLongPollingTransport
    - [ ] JsonProtocal
        - [ ] TextFormate
        - [ ] Binary （not test yet）

## build requirement
1. use [yarn](https://yarnpkg.com/) to support "packagename":"links:../signlar" like path
2. [dotnet core 3.0](https://dot.net)  to run the EchoServer 
3. [wechat dev tool](https://developers.weixin.qq.com/miniprogram/dev/devtools/devtools.html)
