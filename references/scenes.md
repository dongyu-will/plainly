# Scenarios and examples

Read the section relevant to the current task. Every example includes known behavior. Never transfer an example's facts to a different product.

## Names, fields, and actions

Navigation names tell people what they will find. Buttons describe what will happen. Field labels name the actual information; required conditions and formats belong in the label or hint. A placeholder can provide an example, but does not replace a label.

Clarify domain terms with multiple meanings. For example, “settlement” could refer to viewing financial records, reconciling accounts, or initiating a payout. Do not flatten those meanings into “Complete.”

| Known context | Original | Revised |
| --- | --- | --- |
| Navigation opens a list of downloadable invoices | Invoice Management Center | Invoices |
| The button saves a draft without submitting it for review | Submit | Save draft |
| The field contains the delivery address | Shipping address information | Shipping address |

Keep “Delete,” “Disable,” “Archive,” “Cancel,” “Sign out,” and “Close account” distinct according to their actual outcomes. Preserve scope: “Export this page” and “Export all” are different actions.

## Statuses, errors, and confirmations

Distinguish an empty collection from no filter matches, pending loading, failed loading, or missing permission. A blank screen alone does not establish “No data yet.”

Give confirmed causes and available recovery actions. A network timeout proves neither payment failure nor submission failure. If the outcome is unclear, first establish how the system checks it.

Confirmations identify the object and consequence. Destructive-action buttons name the action. Supporting text can carry the consequences without forcing the entire explanation into the button.

| Known context | Original | Revised |
| --- | --- | --- |
| The invoice list loaded successfully and contains no invoices | No data | No invoices yet |
| Search succeeded but no orders match the filters | No data | No orders match these filters |
| Saving definitely failed because the connection dropped; retry is available | Operation failed | Couldn't save because the connection was lost. Try again. |
| Deleting the current draft is irreversible | Are you sure you want to delete the selected item? | Delete this draft? You can't undo this. |

“Sent” is not “Delivered”; “Application submitted” is not “Application approved”; “Saving” is not “Saved.” Keeping already-clear original copy is a valid outcome.

## Onboarding, notices, and customer messages

Onboarding explains the purpose of the current step and what to do. Name “Skip” and “Finish” according to the real flow. Separate practical instructions from promotional claims.

A notice usually states what happened, why it matters, and what to do next. Retain dates, amounts, conditions, and deadlines. Remove greetings or filler when context already supplies them. Add actions such as “View details” only when that destination exists.

Customer replies answer the question first, then explain the available action and relevant conditions. Follow the actual policy; a friendly tone must not invent refunds, compensation, or completion dates.

| Known context | Original | Revised |
| --- | --- | --- |
| A saved address can be selected during checkout | Complete your shipping information to improve your experience | Add a shipping address to use at checkout. |
| This month's bill is attached to the notice | Your monthly billing document has been generated. Please check the attachment. | This month's bill is ready. See the attachment. |
| A confirmed refund takes 3–5 business days to reach the original payment account | Funds will be returned to the original payment account within three to five working days. | Your refund will reach your original payment account in 3–5 business days. |

## Pages, product descriptions, and help

Choose a use that matters to the audience from the product's actual capabilities. Explain it through concrete objects and actions. Use measured benefits only when supported by evidence or a real commitment.

A heading makes one point, supporting text supplies scope or conditions, and the action corresponds to a real destination. Give one recommended revision unless the user asks for alternatives.

| Known context | Original | Revised |
| --- | --- | --- |
| Orders and inventory really appear on the same page | Empowering data management to drive business growth | See orders and inventory in one place. |
| Export requires selecting dates, then choosing Export to download a report | Configure date-based filter parameters before executing the export operation | Choose the dates, then select Export to download the report. |

“Unlimited,” “automatic,” “fastest,” and “free” need support and applicable conditions. Ask when those conditions are unknown.

## Chinese output examples

Keep Chinese copy in Chinese when the target product uses it. Necessary domain or legal terms still matter.

| 已知场景 | 原文案 | 新文案 |
| --- | --- | --- |
| 菜单显示可下载的发票列表 | 发票管理中心 | 发票 |
| 按钮只保存草稿，不送交审核 | 提交 | 保存草稿 |
| 继续操作前必须完成实名认证 | 需完成实名认证方可继续操作 | 先完成实名认证，再继续。 |
| 客服已确认退款需 3–5 个工作日到账 | 款项将于三个至五个工作日内返还至原支付账户 | 退款将在 3–5 个工作日内退回原付款账户。 |

The refund reply is not a 20-character feature description. Keep its payment destination and timeframe intact rather than applying the short-UI default to it.

## Cases that need clarification first

| Source copy and available information | Specific question |
| --- | --- |
| “Settlement management,” with no workflow description | Does this show settlement records or initiate a payout? |
| “Close,” with no account or session details | Does this sign the person out or permanently close their account? |
| “Payment failed,” when the only evidence is a timeout | How is payment status checked after a timeout, and where can the person see the result? |
| “Free to use,” with no pricing policy | Who qualifies, and are there time or usage limits? |

Keep these originals unchanged and mark them “Needs clarification” until their meaning is established.
