1、主要优势：交易通股票程序化接口稳定、高性能、易接入、功能强大、支持跨平台调用、支持大部分券商、安全性及扩展性好；


2、当前接口现状：要么采用模拟股票交易软件界面操作，性能和稳定性很差；要么接口过于底层或复杂导致学习和开发集成的成本高；要么不支持64位程序或跨平台的分布式调用；要么功能过于简单，很难实现想要的策略；

3、底层实现：采用C/C++语言实现，通过TCP直接和交易服务器通讯，确保最佳性能；

4、协议优势：独家实现基于WebSocket技术的通讯协议，可支持分布式的跨平台及跨进程多连接调用，兼容32和64位程序，请求参数和回传数据都是标准JSON格式，易于扩展和解析；

5、系统兼容性：交易通服务程序最低可部署在Windows XP系统中使用，推荐部署到Windows 7及以上的32位及64位系统，包括Server系列服务器。Linux、Mac及手机等系统上也可直接调用；

6、券商兼容性：支持市场上大部分券商，大致八十多家；

7、安全性：承诺无后门、木马或病毒，可在 http://virscan.org/ 提交程序进行检测。上实盘进行交易时，您可以配置操作系统的防火墙功能，针对执行程序ZMTradeService.exe 设置只能访问您所在券商所用的几个交易服务器IP和端口，其他外网请求直接拒绝访问从而确保安全；

8、专业服务：专业技术长期维护，7*12小时在线技术交流(QQ群293765098，加群链接：https://jq.qq.com/?_wv=1027&k=47gPHdN )和远程协作，额外付费可获得线下技术支持服务；

9、交易策略：本中间件不含任何交易策略，也无法获得上层调用程序所使用的策略，而是仅限于接口所提供的功能提供服务，如您需要在上层定制开发策略，可加入在线技术交流群后联系客服沟通；

10、事件通知：提供初始化结果、异步登录结果、委托交易提交结果、实际成交结果、查询行情回报等多个异步操作的事件通知；

11、依赖性：本系统提供的程序包已经包含所有需要的模块，不依赖任何其他软件或组件，也无需启动其它股票软件，除访问您指定的交易服务器外，无需访问其他任何外链服务器即可正常工作；

12、批量操作：普通版及高级版都支持批量提交买入卖出委托、一键打新股和查询多只股票的实时5档行情，批量下单速度与券商有关，具体限制请咨询自己的券商人员；

13、多连接支持：高级版支持同时连接多个交易服务器并同时进行委托交易操作或行情查询，标准版只支持单个连接交易和行情服务器进行操作；

14、高级版支持多账号操作，一键下单、一键撤单无压力，支持板块数据每个交易日的更新；

15、同时支持普通行情、扩展行情、Level2行情的接口服务，取历史行情、当日的分时行情数据、10档行情、逐笔成交等毫无压力。
