# QuickBooks Online Bank Reconciliation: A Step-by-Step Guide for Small Business Owners

## Introduction

Reconciliation is the process of comparing the transactions in QuickBooks Online (QBO) against your bank or credit card statement, line by line, and confirming that the two records agree. When an account is reconciled, you know every deposit, check, and payment on the statement is recorded in QuickBooks exactly once, for the correct amount.

Reconciling every month matters for three practical reasons:

- **It catches errors early.** Duplicates, missing deposits, and wrong amounts are far easier to fix in the month they happen than at tax time.
- **It proves your balances are real.** Your reports are only as trustworthy as the bank balances underneath them. A reconciled account means the QuickBooks balance matches the bank's records.
- **It protects you.** Reconciliation surfaces transactions you do not recognize, including bank errors and unauthorized charges, while you can still dispute them.

This guide walks you through the complete monthly workflow: reviewing the bank feed, reconciling to a zero difference, fixing what stops a reconciliation from balancing, and following a repeatable monthly routine.

### Who this guide is for

This guide is written for small business owners and their staff who use QuickBooks Online to manage a business checking, savings, or credit card account. No accounting background is assumed. Terms are defined in plain language as they appear, and a [glossary](#glossary) collects the key definitions in one place.

### What you need before you start

- Access to QuickBooks Online with permission to view and edit bank accounts.
- The bank or credit card statement for the period you are reconciling, in print or PDF. You will copy the **ending balance** and **ending date** directly from this statement.
- About 20 to 30 minutes for your first reconciliation. Later ones are faster.

## Before You Begin

Work through this checklist before you open the Reconcile page; most reconciliation problems start before the reconciliation does, and this list prevents the common ones.

- [ ] **Reconcile in order.** If several months are unreconciled, start with the oldest month and finish it completely before moving to the next. Each month's beginning balance depends on the month before it.
- [ ] **Use the statement, not the bank's website.** The balances on your bank's home page move every day. The statement is a fixed record of one period, and it is the record your reconciliation must match.
- [ ] **Enter transactions that never reach the bank feed.** Record hand-written checks, cash deposits, and any bank charges or interest that did not download, so they are available to check off.
- [ ] **Clear the bank feed first.** Finish Part 1 of this guide (review, categorize, and match downloaded transactions) before reconciling. Reconciling against an unreviewed feed almost always ends in a difference you cannot explain.
- [ ] **Do not edit older, already reconciled transactions.** Changing or deleting a transaction from a prior, reconciled period changes that period's totals and creates a discrepancy in the current one. If an old transaction is wrong, read Part 3 first.

> **Note:** QuickBooks saves your reconciliation progress when you choose **Save for later**, so you can start, stop, and return without losing checked items. There is no penalty for pausing.

## Part 1: Connect Your Account and Review the Bank Feed

The bank feed is a one-way download of transactions from your bank into QuickBooks. Reconciliation quality is decided here: the feed is where duplicates are born and where most missing transactions hide. This part connects the account, then works the feed clean.

### Connect a bank or credit card account

Skip this section if your account is already connected.

1. Go to **Transactions**, then **Bank transactions**.
2. Select **Connect account**.
3. Search for your bank or credit card provider, select it, and sign in with your bank credentials.
4. Choose the account you want to connect and the date you want QuickBooks to start downloading transactions from.
5. Select **Connect**.

QuickBooks downloads the transactions into the **For review** tab of the Banking page. Nothing there is part of your books yet; a transaction counts only once you add or match it below.

### Review and categorize transactions

Work through the **For review** tab from oldest to newest.

1. Select a transaction to open its detail.
2. Confirm the **Category**, the account that describes what the money was for, such as Office Supplies or Fuel. The category places the transaction correctly on your reports.
3. Add the **Vendor** (for money out) or **Customer** (for money in) if it is blank; consistent names keep reports and searches useful.
4. Select **Add**. The transaction moves out of **For review** and into your books and the account register.

> **Tip:** QuickBooks suggests the category it used last time for similar purchases. Check the suggestion before accepting it; a wrong suggestion accepted ten times is ten corrections later.

### Match transactions QuickBooks already knows about

Some downloaded transactions are the bank's copy of something you already recorded, for example an invoice payment you entered when a customer paid. Adding these a second time would double-count them.

1. If a transaction in **For review** shows a **Match** option, select **Find match** to see the entry QuickBooks believes already exists for it.
2. Confirm the amount and date agree with the downloaded transaction.
3. Select the matching entry and choose **Save**. The downloaded transaction is linked to the existing entry instead of creating a new one.

### Exclude duplicates and items that do not belong

Occasionally the feed delivers the same transaction twice, or one you already recorded by another route. Do not add these.

1. In **For review**, select the checkbox next to each transaction you want to remove.
2. Select **Exclude**.

Excluded transactions move to the **Excluded** tab, out of your books and out of the reconciliation. If you exclude something by mistake, you can undo it from the **Excluded** tab.

> **Warning:** Exclude is for true duplicates only. Excluding a transaction that represents real money movement makes your balance wrong by that amount, and the error surfaces as a reconciliation difference. When in doubt, match it or add it; do not exclude it.

When the **For review** tab is empty for the statement period, you are ready to reconcile.

## Part 2: Run Your First Reconciliation

This procedure reconciles one account for one statement period. The goal is strict: when you finish, the **Difference** field must read **0.00**.

1. Go to **Accounting**, then **Reconcile**.
2. In the **Account** dropdown, choose the bank or credit card account you are reconciling.
3. Check the **Beginning balance** QuickBooks shows. It is the ending balance of your last completed reconciliation for this account, and it should match the beginning balance printed on your statement. If it does not, stop and read Part 3 before continuing; reconciling on top of a wrong beginning balance cannot produce a correct result.
4. In the **Ending balance** field, type the ending balance exactly as printed on your bank statement.
5. In the **Ending date** field, enter the statement's ending date, not today's date.
6. Select **Start reconciling**.

   The reconciliation screen lists this account's transactions recorded in QuickBooks: payments and checks on one side, deposits and other credits on the other.

7. Work down your bank statement one line at a time. For every transaction on the statement, select the checkbox next to the matching transaction on the reconciliation screen.

   As you check items, QuickBooks updates the totals at the top of the screen, including the **Difference**: the statement ending balance minus the checked total.

8. If a statement item is missing from the screen, do not check a similar item to force a fit. Leave the reconciliation, add the missing transaction (from **+ New**, or from the bank feed if it is still in **For review**), then return. Your checked items are saved while you work.
9. If an amount on screen disagrees with the statement, open the transaction, correct the amount to match your source document (the receipt, invoice, or check copy, not just the statement), save, and return.
10. Continue until every line on the statement is checked and the **Difference** reads **0.00**.

    Transactions left unchecked are items the bank does not show yet, such as a check you mailed that has not cleared. Leaving them unchecked is correct; they carry forward to a later period.

11. Choose how to end the session:
    - Select **Finish now** if the difference is 0.00. QuickBooks marks every checked transaction as reconciled and locks the period's totals into the account history.
    - Select **Save for later** if you need to stop, or the difference is not yet zero. You can resume anytime from **Accounting > Reconcile**.
12. After **Finish now**, QuickBooks confirms the reconciliation is complete and offers to view or print the **reconciliation report**. Save a copy for each period. Past reports are also available anytime from **Accounting > Reconcile > History by account**.

> **Warning:** If you finish while the difference is not zero, QuickBooks posts the difference as an adjustment transaction rather than finding the error. The adjustment makes the screen agree without making the books right. Treat a nonzero difference as a problem to solve in Part 3, not a shortcut.

## Part 3: Troubleshooting

Find the problem that matches what you see, then follow the fix in order. Do not finish the reconciliation with a difference while a fix remains untried.

| Problem | Likely cause | Fix |
| --- | --- | --- |
| The **Difference** is not zero, and you cannot see why | One or more statement items are unchecked, checked in error, or recorded for a different amount | Sort the reconciliation screen by amount and compare against the statement again. Then divide the difference by two and look for a transaction of that size: a halved difference usually means an item was checked on the wrong side, or a deposit was entered as a payment. |
| The **Difference** equals the amount of one transaction | That transaction is missing, duplicated, or checked when it should not be | Search the account register for the amount. Add it if missing (Part 1), delete it if entered twice, or uncheck it if it is not on this statement. |
| A transaction on the statement is missing from QuickBooks | It never downloaded, was excluded by mistake, or was recorded in a different account | Check the **Excluded** tab of the bank feed and restore it if it is there. Check your other account registers. If it is nowhere, enter it manually with the statement date. |
| The same transaction appears twice in QuickBooks | It was both added from the bank feed and entered by hand, or added instead of matched | Open both copies. Keep the one linked to the bank feed (or tied to an invoice or bill) and delete the other. Next time, use **Find match** before adding. |
| A checked amount does not match the statement | A data entry error, a bank fee bundled into the amount, or a partially paid invoice | Open the transaction and compare it to the source document. Correct the amount, or record the bundled fee as its own transaction so both pieces check off separately. |
| The **Beginning balance** does not match the statement | A transaction from a reconciled period was edited or deleted, or the account's opening balance was entered incorrectly | Run the **Reconciliation Discrepancy** report (go to **Reports** and search for it) to see which reconciled transactions changed. Restore the original amounts or dates. If the account has never been reconciled, the opening balance entry itself is wrong and must be corrected before the first reconciliation can balance. |
| A check from an earlier month still has not cleared | The check was lost, never mailed, or the payee never deposited it | Contact the payee. If the check is lost, void it in QuickBooks and reissue it. Do not delete old outstanding checks to clean up the list; deleting one changes a prior balance. |
| A whole reconciliation needs to be redone | The wrong ending balance or date was used, or many items were checked in error | An entire reconciliation can be undone from **Accounting > Reconcile > History by account**, but the **Undo** option is available only to users signed in through QuickBooks Online Accountant, such as your bookkeeper. Individual transactions can be unreconciled one at a time in the account register by clicking the **R** (reconciled) status in the status column until it clears. |

> **Note:** Every change to a reconciled transaction is recorded in the audit history: go to **Settings**, then **Audit log**. It is the fastest way to confirm whether a discrepancy came from an edit, a deletion, or an import.

## Part 4: The Monthly Reconciliation Checklist

Reconciliation works best as a short monthly routine, not a yearly rescue project. Repeat these steps, in the same order, for every bank and credit card account.

**Prepare**

- [ ] Download or print the statement for the month as soon as it is available.
- [ ] Enter hand-written checks, cash deposits, interest, and bank fees that do not download through the feed.

**Review**

- [ ] Work the **For review** tab of the bank feed to empty: categorize, add, or match every transaction for the period.
- [ ] Scan the **Excluded** tab and restore anything excluded by mistake.

**Reconcile**

- [ ] Confirm the **Beginning balance** on the Reconcile page matches the statement.
- [ ] Enter the statement's **Ending balance** and **Ending date** and select **Start reconciling**.
- [ ] Check off every transaction that appears on the statement, working in statement order.
- [ ] Resolve any difference using Part 3 until the **Difference** reads **0.00**.
- [ ] Select **Finish now**, then save or print the **reconciliation report** for the period.

**Wrap up**

- [ ] Glance through the transactions left unchecked. Each one should be a recent, genuinely outstanding item. Investigate anything older than 60 days.
- [ ] Note any transaction you did not recognize, even if it reconciled, and follow up on it the same week.
- [ ] Reconcile the next account, or schedule next month's session while this one is fresh.

## Glossary

**Reconciliation.** The process of comparing the transactions recorded in QuickBooks against a bank or credit card statement and confirming that both records agree for the same period.

**Beginning balance.** The balance QuickBooks starts a reconciliation with. It equals the ending balance of the last completed reconciliation for that account, so an error in one month carries into the next until fixed.

**Ending balance.** The balance printed on your bank statement for the last day of the statement period. You type it into QuickBooks to start the reconciliation; it is the target the reconciliation must reach.

**Cleared.** A transaction has cleared when the bank has processed it and it appears on a statement. Checking its box during reconciliation marks it cleared for that period.

**Difference.** The field at the top of the reconciliation screen showing how far the checked transactions are from the statement ending balance. A finished reconciliation must have a difference of 0.00.

**Outstanding transaction.** A transaction recorded in QuickBooks that has not yet appeared on a statement, such as a mailed check the payee has not deposited. Outstanding transactions are normal and stay unchecked until they clear.

**Audit history.** The record QuickBooks keeps of changes to transactions, available in **Settings > Audit log**. It shows who created, edited, or deleted a transaction and when, including changes to transactions in reconciled periods.

**Reconciliation report.** The summary saved each time you finish a reconciliation, listing the period, the beginning and ending balances, and the transactions that cleared. Retrieve past reports from **Accounting > Reconcile > History by account**.

## Getting Help

If a reconciliation will not balance after you have worked through Part 3, stop before forcing it. A difference that survives honest troubleshooting usually means an earlier period needs attention, and an accountant can undo and rebuild the reconciliation. Bring three things to that conversation: the statement that will not reconcile, the **Reconciliation Discrepancy** report, and a note of anything unusual you noticed, such as an unrecognized transaction or a payment recorded twice.

For product questions, the help topics inside QuickBooks Online (select the **Help** icon and search for "reconcile") cover the current version of every screen named here. Labels change over time; the workflow, review the feed, reconcile to zero, investigate every difference, does not.

---

*Guide written and maintained by Brittany Nation, QuickBooks Certified ProAdvisor, Deva Gana LLC. An original portfolio writing sample, not affiliated with or endorsed by Intuit Inc. QuickBooks and QuickBooks Online are trademarks of Intuit Inc.*
