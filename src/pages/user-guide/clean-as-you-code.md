---
title: 乾淨的寫程式碼
url: /user-guide/clean-as-you-code/
---

## 什麼是乾淨的寫程式碼?

乾淨的寫程式碼是一種能提升程式碼品質的方法，它消除了傳統方法帶來的許多挑戰。身為
一名開發人員，您將專注於以高標準撰寫新程式碼並且為它負責。SonarQube 能提供讓您
設定高標準的工具，並且讓您為達到那些標準而感到自豪。

## 專注於 新程式碼（New Code）

用乾淨程式碼撰寫方式，您應該一直專注在 新程式碼（New Code）上（在新 程式碼週期（New Code Period）間新增或更改的程式碼）並且確認
您寫的程式碼是乾淨且安全的。

新程式碼週期 可於不同層級上被設定（全域、專案、與 [開發人員版本](https://redirect.sonarsource.com/editions/developer.html)
或 [更高級版本](https://www.sonarsource.com/plans-and-pricing/)）。依據您設定的層級，您可以依您的狀況調整適當的「新程式碼週期」起始時間。

有關「新程式碼週期」及其設定的更多資訊，請查看 [設定新程式碼週期](/project-administration/new-code-period/)。

## 個人的責任

有乾淨的程式碼撰寫，您將不再為他人的程式碼負責。您擁有自己新程式碼的品質與保障。如果您新增了 問題（Issue），SonarQube 會自動指派給您，
讓您可以維護自己的程式碼。

有關「問題」與它們如何被指派的更多資訊，請查看 [問題（Issue）](/user-guide/issues/) 文件。

## 品質門檻（Quality Gates）

「品質門檻」是一組能告訴您專案是否可以被釋出了的情況。使用乾淨的程式碼撰寫，
您的品質門檻應該要：

* **聚焦於新程式碼指標** – 當您的「品質門檻」聚焦於新程式碼指標（像是內建的 Sonar way 品質門檻），新的功能將會被乾淨的交付。
只要您的品質門檻是綠燈，您的發布將會持續改善。
* **高標準的制定與執行** – 當一些標準於新的程式碼上被制訂與執行，您不會擔心舊程式碼沒有達到那些標準並且需要整理其他人的程式碼。
 您可以為 _您的_ 程式碼有達到高標準而驕傲。當一個專案沒有達到這些高標準時，它不會通過品質門檻，很顯然的，它還不能被發布。

有關「品質門檻」與確認「品質門檻」是否有在執行您的標準的更多資訊，請查看 [品質門檻](/user-guide/quality-gates/) 文件。

## 合併請求（Pull Request）之分析

您可以用「合併請求」分析和修飾來確保您的程式碼符合標準。合併請求分析使您可以在 SonarQube 使用者介面中
查看「合併請求」裡的「品質門檻」（Quality Gates）。您接著可以直接在 ALM 的介面中
使用 SonarQube 問題來裝飾「合併請求」。

有關設置「合併請求」分析和裝飾的更多資訊，請查看 [合併請求](/analysis/pull-request/) 文件。
