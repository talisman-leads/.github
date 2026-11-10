## TalismanLeads

**Bulk phone, email and carrier checks, from a website, a Telegram bot or a REST API.**

Find out which numbers are on WhatsApp, Telegram or iMessage, which emails have a LinkedIn or PayPal account, and which carrier and line type each number has, from a few hundred entries to millions. Pay as you go from one balance, at the same price wherever you order.

[Website](https://talismanleads.io) · [API docs](https://docs.talismanleads.io) · [Pricing](https://talismanleads.io/pricing) · [Free tools](https://talismanleads.io/free-tools) · [Blog](https://talismanleads.io/blog) · [Telegram bot](https://t.me/TalismanLeadsV1bot)

### Start with the API

```bash
curl -X POST "https://api.talismanleads.io/v1/estimates" \
  -H "Authorization: Bearer $TALISMANLEADS_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"checker":"whatsapp_status_detection","entries":["+14155550142","+12125550187"]}'
```

The full guide, with complete Python and Node.js examples, is in **[talismanleads-api](https://github.com/talisman-leads/talismanleads-api)**. Every checker also has its own repo with a ready-to-run example.

### 49 checkers

#### Messaging apps

| Checker | Takes | Repo |
| --- | --- | --- |
| [iMessage Number Checker](https://docs.talismanleads.io/checkers/imessage_number_checker) | Phone numbers | [imessage-number-checker-api](https://github.com/talisman-leads/imessage-number-checker-api) |
| [MAX Number Checker](https://docs.talismanleads.io/checkers/max_number_checker) | Phone numbers | [max-number-checker-api](https://github.com/talisman-leads/max-number-checker-api) |
| [MAX Profile Checker](https://docs.talismanleads.io/checkers/max_profile_checker) | Phone numbers | [max-profile-checker-api](https://github.com/talisman-leads/max-profile-checker-api) |
| [Messenger Number Checker](https://docs.talismanleads.io/checkers/messenger_number_checker) | Phone numbers | [messenger-number-checker-api](https://github.com/talisman-leads/messenger-number-checker-api) |
| [RCS Number Checker](https://docs.talismanleads.io/checkers/rcs_number_checker) | Phone numbers | [rcs-number-checker-api](https://github.com/talisman-leads/rcs-number-checker-api) |
| [Telegram Activity Checker](https://docs.talismanleads.io/checkers/telegram_activity_checker) | Phone numbers | [telegram-activity-checker-api](https://github.com/talisman-leads/telegram-activity-checker-api) |
| [Telegram Number Checker](https://docs.talismanleads.io/checkers/telegram_number_checker) | Phone numbers | [telegram-number-checker-api](https://github.com/talisman-leads/telegram-number-checker-api) |
| [Telegram Profile Checker](https://docs.talismanleads.io/checkers/telegram_profile_checker) | Phone numbers | [telegram-profile-checker-api](https://github.com/talisman-leads/telegram-profile-checker-api) |
| [Viber Activity Checker](https://docs.talismanleads.io/checkers/viber_activity_checker) | Phone numbers | [viber-activity-checker-api](https://github.com/talisman-leads/viber-activity-checker-api) |
| [Viber Number Checker](https://docs.talismanleads.io/checkers/viber_number_checker) | Phone numbers | [viber-number-checker-api](https://github.com/talisman-leads/viber-number-checker-api) |
| [WhatsApp Business Checker](https://docs.talismanleads.io/checkers/whatsapp_business_checker) | Phone numbers | [whatsapp-business-checker-api](https://github.com/talisman-leads/whatsapp-business-checker-api) |
| [WhatsApp Number Checker](https://docs.talismanleads.io/checkers/whatsapp_status_detection) | Phone numbers | [whatsapp-number-checker-api](https://github.com/talisman-leads/whatsapp-number-checker-api) |
| [WhatsApp Profile Picture, Age, Ethnicity Checker](https://docs.talismanleads.io/checkers/whatsapp_profile_checker) | Phone numbers | [whatsapp-profile-checker-api](https://github.com/talisman-leads/whatsapp-profile-checker-api) |

#### Social networks

| Checker | Takes | Repo |
| --- | --- | --- |
| [Facebook Email Checker](https://docs.talismanleads.io/checkers/facebook_email_checker) | Email addresses | [facebook-email-checker-api](https://github.com/talisman-leads/facebook-email-checker-api) |
| [Facebook Number Checker](https://docs.talismanleads.io/checkers/facebook_number_checker) | Phone numbers | [facebook-number-checker-api](https://github.com/talisman-leads/facebook-number-checker-api) |
| [Instagram Email Checker](https://docs.talismanleads.io/checkers/instagram_email_checker) | Email addresses | [instagram-email-checker-api](https://github.com/talisman-leads/instagram-email-checker-api) |
| [Instagram Number Checker](https://docs.talismanleads.io/checkers/instagram_number_checker) | Phone numbers | [instagram-number-checker-api](https://github.com/talisman-leads/instagram-number-checker-api) |
| [LinkedIn Email Checker](https://docs.talismanleads.io/checkers/linkedin_email_checker) | Email addresses | [linkedin-email-checker-api](https://github.com/talisman-leads/linkedin-email-checker-api) |
| [LinkedIn Number Checker](https://docs.talismanleads.io/checkers/linkedin_number_checker) | Phone numbers | [linkedin-number-checker-api](https://github.com/talisman-leads/linkedin-number-checker-api) |
| [LinkedIn Profile, Gender, Industry, Job Title, Salary Checker](https://docs.talismanleads.io/checkers/linkedin_profile_checker) | Email addresses | [linkedin-profile-checker-api](https://github.com/talisman-leads/linkedin-profile-checker-api) |
| [Snapchat Number Checker](https://docs.talismanleads.io/checkers/snapchat_number_checker) | Phone numbers | [snapchat-number-checker-api](https://github.com/talisman-leads/snapchat-number-checker-api) |
| [Threads Number Checker](https://docs.talismanleads.io/checkers/threads_number_checker) | Phone numbers | [threads-number-checker-api](https://github.com/talisman-leads/threads-number-checker-api) |
| [TikTok Number Checker](https://docs.talismanleads.io/checkers/tiktok_number_checker) | Phone numbers | [tiktok-number-checker-api](https://github.com/talisman-leads/tiktok-number-checker-api) |
| [VK Number Checker](https://docs.talismanleads.io/checkers/vk_number_checker) | Phone numbers | [vk-number-checker-api](https://github.com/talisman-leads/vk-number-checker-api) |

#### Shopping, streaming and services

| Checker | Takes | Repo |
| --- | --- | --- |
| [Airbnb Number Checker](https://docs.talismanleads.io/checkers/airbnb_number_checker) | Phone numbers | [airbnb-number-checker-api](https://github.com/talisman-leads/airbnb-number-checker-api) |
| [Amazon Email Checker](https://docs.talismanleads.io/checkers/amazon_email_checker) | Email addresses | [amazon-email-checker-api](https://github.com/talisman-leads/amazon-email-checker-api) |
| [Amazon Number Checker](https://docs.talismanleads.io/checkers/amazon_number_checker) | Phone numbers | [amazon-number-checker-api](https://github.com/talisman-leads/amazon-number-checker-api) |
| [Apple ID Email Checker](https://docs.talismanleads.io/checkers/apple_id_email_checker) | Email addresses | [apple-id-email-checker-api](https://github.com/talisman-leads/apple-id-email-checker-api) |
| [Apple ID Number Checker](https://docs.talismanleads.io/checkers/apple_id_number_checker) | Phone numbers | [apple-id-number-checker-api](https://github.com/talisman-leads/apple-id-number-checker-api) |
| [DHL Number Checker](https://docs.talismanleads.io/checkers/dhl_number_checker) | Phone numbers | [dhl-number-checker-api](https://github.com/talisman-leads/dhl-number-checker-api) |
| [Gmail Email Checker](https://docs.talismanleads.io/checkers/gmail_email_checker) | Email addresses | [gmail-email-checker-api](https://github.com/talisman-leads/gmail-email-checker-api) |
| [Microsoft Number Checker](https://docs.talismanleads.io/checkers/microsoft_number_checker) | Phone numbers | [microsoft-number-checker-api](https://github.com/talisman-leads/microsoft-number-checker-api) |
| [Netflix Email Checker](https://docs.talismanleads.io/checkers/netflix_email_checker) | Email addresses | [netflix-email-checker-api](https://github.com/talisman-leads/netflix-email-checker-api) |
| [Netflix Number Checker](https://docs.talismanleads.io/checkers/netflix_number_checker) | Phone numbers | [netflix-number-checker-api](https://github.com/talisman-leads/netflix-number-checker-api) |
| [PayPal Email Checker](https://docs.talismanleads.io/checkers/paypal_email_checker) | Email addresses | [paypal-email-checker-api](https://github.com/talisman-leads/paypal-email-checker-api) |
| [Spotify Email Checker](https://docs.talismanleads.io/checkers/spotify_email_checker) | Email addresses | [spotify-email-checker-api](https://github.com/talisman-leads/spotify-email-checker-api) |
| [Temu Number Checker](https://docs.talismanleads.io/checkers/temu_number_checker) | Phone numbers | [temu-number-checker-api](https://github.com/talisman-leads/temu-number-checker-api) |
| [Wheely Number Checker](https://docs.talismanleads.io/checkers/wheely_number_checker) | Phone numbers | [wheely-number-checker-api](https://github.com/talisman-leads/wheely-number-checker-api) |

#### Crypto exchanges

| Checker | Takes | Repo |
| --- | --- | --- |
| [Binance Number Checker](https://docs.talismanleads.io/checkers/binance_number_checker) | Phone numbers | [binance-number-checker-api](https://github.com/talisman-leads/binance-number-checker-api) |
| [CoinW Email Checker](https://docs.talismanleads.io/checkers/coinw_email_checker) | Email addresses | [coinw-email-checker-api](https://github.com/talisman-leads/coinw-email-checker-api) |
| [CoinW Number Checker](https://docs.talismanleads.io/checkers/coinw_number_checker) | Phone numbers | [coinw-number-checker-api](https://github.com/talisman-leads/coinw-number-checker-api) |
| [Crypto.com Email Checker](https://docs.talismanleads.io/checkers/crypto_com_email_checker) | Email addresses | [crypto-com-email-checker-api](https://github.com/talisman-leads/crypto-com-email-checker-api) |
| [Crypto.com Number Checker](https://docs.talismanleads.io/checkers/crypto_com_number_checker) | Phone numbers | [crypto-com-number-checker-api](https://github.com/talisman-leads/crypto-com-number-checker-api) |
| [HTX Email Checker](https://docs.talismanleads.io/checkers/htx_email_checker) | Email addresses | [htx-email-checker-api](https://github.com/talisman-leads/htx-email-checker-api) |
| [HTX Number Checker](https://docs.talismanleads.io/checkers/htx_number_checker) | Phone numbers | [htx-number-checker-api](https://github.com/talisman-leads/htx-number-checker-api) |
| [KuCoin Email Checker](https://docs.talismanleads.io/checkers/kucoin_email_checker) | Email addresses | [kucoin-email-checker-api](https://github.com/talisman-leads/kucoin-email-checker-api) |
| [KuCoin Number Checker](https://docs.talismanleads.io/checkers/kucoin_number_checker) | Phone numbers | [kucoin-number-checker-api](https://github.com/talisman-leads/kucoin-number-checker-api) |
| [OKX Number Checker](https://docs.talismanleads.io/checkers/okx_number_checker) | Phone numbers | [okx-number-checker-api](https://github.com/talisman-leads/okx-number-checker-api) |

#### Carrier and line type

| Checker | Takes | Repo |
| --- | --- | --- |
| [Number Carrier Lookup](https://docs.talismanleads.io/checkers/global_carrier_checker) | Phone numbers | [phone-carrier-lookup-api](https://github.com/talisman-leads/phone-carrier-lookup-api) |

### Guides and resources

Articles, free tools and how-tos are collected in **[talismanleads-resources](https://github.com/talisman-leads/talismanleads-resources)**.

<sub>Questions: [support@talismanleads.io](mailto:support@talismanleads.io). Security reports: see our [Vulnerability Disclosure Program](https://talismanleads.io/vulnerability-disclosure-program).</sub>
