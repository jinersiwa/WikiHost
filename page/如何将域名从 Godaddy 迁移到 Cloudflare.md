# 如何将域名从 Godaddy 迁移到 Cloudflare

在域名管理中，选择一家合适的服务商至关重要。Godaddy 的域名续费价格高达每年 159 元，而 Cloudflare 的续费价格仅为 80 元。对于一个即将到期的域名，我决定将其转移到 Cloudflare 后再进行续费。以下是详细的迁移步骤。

## 一、将域名添加到 Cloudflare

1. **登录 Cloudflare**：访问 [Cloudflare 控制台](https://dash.cloudflare.com/)，选择添加域，将你的域名添加到 Cloudflare。
   ![步骤 1](https://bbtdd.com/img/7941347794.webp)

2. **自动读取 DNS 配置**：添加域名后，Cloudflare 会自动读取现有的 DNS 配置并添加到其系统中。继续按照提示操作。
   ![步骤 2](https://bbtdd.com/img/4213883475061068.webp)

3. **更换名称服务器**：DNS 配置完成后，Cloudflare 会提示你去 Godaddy 更换名称服务器。记录下提示的域名服务器，准备进行下一步操作。
   ![步骤 3](https://bbtdd.com/img/5380120520.webp)

## 二、转移域名服务器

> 登录 Godaddy，选择你需要转移的域名，设置域名服务器，填入 Cloudflare 提供的域名服务器。
>
> ![步骤 4](https://bbtdd.com/img/913650279.webp)
>
> 保存设置后返回 Cloudflare，查看域状态。如果显示为活动状态，则表示域名服务器转移成功，接下来可以开始域名转移。

## 三、域名转移流程

1. **登录 Godaddy**：选择你要转移的域名，点击操作按钮。
   ![步骤 5](https://bbtdd.com/img/450349097916945.webp)

2. **选择转移选项**：选择“转移到另一个注册商”选项。
   ![步骤 6](https://bbtdd.com/img/406423088387598.webp)

3. **获取授权码**：按照提示继续操作，Godaddy 会生成一个转移授权码。记录下这个授权码，后续在 Cloudflare 中会用到。
   ![步骤 7](https://bbtdd.com/img/34018402856.webp)

4. **登录 Cloudflare**：点击“转移域”按钮，继续操作。域名转移通常需要续费一年，Cloudflare 的续费价格为 80 元，比 Godaddy 的 159 元更具性价比。
   ![步骤 8](https://bbtdd.com/img/033121294613.webp)

5. **输入授权码**：将 Godaddy 提供的授权码复制到 Cloudflare 的对应输入框中，点击确认。
   ![步骤 9](https://bbtdd.com/img/1135028099.webp)

6. **支付**：需要提供扣款卡信息，即将开始转移。注意，国内卡无法完成扣款，建议使用国际虚拟卡。👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)
   ![步骤 10](https://bbtdd.com/img/13049963.webp)

7. **确认转出**：登录 Godaddy 确认域名转出操作。
   ![步骤 11](https://bbtdd.com/img/385783441506.webp)

8. **完成转移**：当你收到确认邮件时，域名转移流程已顺利完成。
   ![步骤 12](https://bbtdd.com/img/2024231565662.webp)

通过以上步骤，你可以轻松将域名从 Godaddy 迁移到 Cloudflare，享受更实惠的价格和更高效的管理服务。