# 订阅 OpenAI 服务和 ChatGPT Plus 升级的常见问题及解决方案

## 问题一：如何取消 ChatGPT Plus 的自动扣费/订阅？

ChatGPT Plus 采用订阅制，每个月 20 美金。假如你开通了 ChatGPT Plus，订阅到期后，OpenAI 会尝试从你的账户扣款。此时如果你的账户里的余额不足 20 美元，几次扣款都没成功，可能就会被 OpenAI 锁定账户。那么该如何避免呢，及时取消订阅就行了。

至于怎么取消，操作简单。在网页上操作就可以：

### 1.1 登录 ChatGPT 后，点击左下角用户头像

![登录 ChatGPT](https://bbtdd.com/img/4945581529517754.webp)

### 1.2 在弹窗中，点击「My plan」

![点击 My plan](https://bbtdd.com/img/6237360036110.webp)

### 1.3 点击「Manage my subscription」

![点击 Manage my subscription](https://bbtdd.com/img/06600331.webp)

### 1.4 在跳转订阅的界面，点击「取消方案」/ Cancel

![取消方案](https://bbtdd.com/img/831753062295910.webp)

## 问题二：付款成功但 ChatGPT Plus 未生效如何申请退款？

订阅 ChatGPT Plus 时，偶尔会出现扣款 20 美元，但是用户仍未升级成功的情况。那么此时该怎么办？

别慌，可以手动申请退款，退款一般 7-14 个工作日退回，以下是申请教程。

### 2.1 前往 [https://help.openai.com](https://help.openai.com)，在界面右下角点击客服发起对话

![前往 help.openai.com](https://bbtdd.com/img/611511184857008.webp)

### 2.2 依次选择 [Billings] -> [I paid for ChatGPT Plus but can’t access the service.]

![选择 Billings](https://bbtdd.com/img/344849429.webp)

### 2.3 点击 [yes]，并填写自己的邮箱，并全屏截图

购买时间和 ChatGPT 界面全屏截图（截图可以看到电脑的时间）

**注意**，购买时间最好用 UTC 时间而非 GMT +8 北京时间。

UTC 时间 = 北京时间 - 8 小时

![填写邮箱](https://bbtdd.com/img/3645722426701.webp)

## 问题三：ChatGPT Plus 自动扣费失败，该如何续订？

ChatGPT Plus 的订阅服务是每个月 20 美元，每月都会自动扣费。如果你订阅了 ChatGPT Plus，但账户余额不足 20 美元，OpenAI 就会在第一次扣费失败后暂停你的 Plus 订阅，而且不会再尝试扣费了。想要继续享受服务？按照这个指南操作就好。

### 3.1 Plus 还在有效期内

如果你没看到“Renew”按钮，说明你的 Plus 服务还没到期。等到服务过期后（通常是一天后），就可以按照以下步骤重新订阅。

### 3.2 登录到 ChatGPT，找到左下角点击“Renew Plus”

![点击 Renew Plus](https://bbtdd.com/img/51513242821261.webp)

### 3.3 在弹出的窗口中，选择“Upgrade To Plus”

![选择 Upgrade To Plus](https://bbtdd.com/img/583648385.webp)

### 3.4 复制支付页面网址

当你到了支付页面，复制那个以 `pay.openai.com` 开头的完整网址，记得不要在支付页面输入任何信息。如果不小心输入了，回到上一步，重新来过，再复制网址。

![复制支付页面网址](https://bbtdd.com/img/07093890.webp)

### 3.5 通过 WildCard 一键升级 ChatGPT Plus

登录到 [WildCard](https://bbtdd.com/WildCard)，点击“一键升级”。

![登录 WildCard](https://bbtdd.com/img/90750109936.webp)

将复制的网址粘贴到指定的地方，点击 [一键升级]，然后会跳出窗口，点击【确定】，等待几分钟即可完成。

## 问题四：升级 ChatGPT-4.0 出现「您的银行卡被拒绝/your card has been declined」怎么办？如何解决 OpenAI 支付问题？

在试着订阅 ChatGPT Plus 或者使用 OpenAI 的 API 时，你可能会遇到一些报错信息。

![银行卡被拒绝](https://bbtdd.com/img/974279209042.webp)

这种情况，别担心，可以试试以下几个解决方法：

### 4.1 网络环境风险过高，用浏览器插件搞定

咱们知道，OpenAI 和 Midjourney 这类服务是通过 Stripe 来处理支付的。Stripe 在处理绑卡或支付时，会对用户的访问 IP 做一个风险评估。如果你的 IP（大多数时候是因为用了代理）是很多人在绑卡或支付时用过的，那么 Stripe 就可能因为风险过高而拒绝操作。

要知道，👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard) 其实是借记卡，它没有信用额度，如果卡里没钱，那么绑定就不会成功。即便是绑卡过程，并非真的消费，但如果余额为零，也是无法通过预扣款的验证的。所以，检查一下余额，确保有足够的钱在卡里。

## 问题五：升级 ChatGPT Plus 出现「我们未能验证您的支付方式/we are unable to authenticate」怎么办？如何解决支付问题？

在订阅 ChatGPT-4.0 时，有时候会出现以下报错：

text
We are unable to authenticate your payment method.
我们未能验证您的支付方式。


![支付方式未验证](https://bbtdd.com/img/002024519.webp)

出现这个错误，基本上是因为当前的代理 IP 使用人数过多，导致 IP 被 OpenAI 的 Stripe 风控，然后拒绝支付，此时千万不要多次点击 [Subscribe]，因为 3 次支付失败会被判定为异常支付，可能会失去后续升级 Plus 的资格。

**解决方案**如下：

将支付页面的链接全选并复制

![复制支付页面链接](https://bbtdd.com/img/8938403143641294.webp)

然后粘贴到 [WildCard](https://bbtdd.com/WildCard) 中，点击 [一键升级]，然后会跳出窗口，点击确定，等待几分钟即可完成。

![粘贴到 WildCard](https://bbtdd.com/img/9734501001246.webp)

当完成升级后，会给你支付宝绑定的手机号码发短信，提示你升级成功。