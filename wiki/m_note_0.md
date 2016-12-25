# 參考資料
一般寫法
- [Rails 4.0 ckeditor + paperclip - 我在ALPHACamp 52天 ~ 史蒂芬.陳的碎碎念](http://stevenchentw.blogspot.tw/2016/04/rails-40-ckeditor-paperclip-alphacamp-52.html)
- [How to Install and Use Ckeditor and Paperclip in Rails App - Yu-Chieh’s Blog (Y.C. Chang)](http://andystu.github.io/blog/2015/02/26/how-to-install-and-use-ckeditor-and-paperclip-in-rails-app/)
- [HOW TO INSTALL CKEDITOR & PAPERCLIP - PART 1 - Hi there, I'm Shani](http://www.shanirivers.me/posts/how-to-install-ckeditor-paperclip)
- 客制ckeditor的UI：[神調校讓 CKEditor 更好用 « 要改的地方太多了，那就改天吧](http://jimmysu.logdown.com/posts/289076-setting-ckeditor)
- [Build a Blog with Ruby on Rails – Part 1 | Scotch](https://scotch.io/tutorials/build-a-blog-with-ruby-on-rails-part-1)，有用ckeditor
  - [kinsomicrote/scotch-blog GitHub](https://github.com/kinsomicrote/scotch-blog)


JC流寫法
- [Rails + ckeditor + 自幹檔案上傳系統 - 教學 - Rails Fun!! Ruby & Rails 中文論壇](http://railsfun.tw/t/rails-ckeditor/319)
  - [JokerCatz/example-rails-ckeditor-uploader - GitHub](https://github.com/JokerCatz/example-rails-ckeditor-uploader)
  - JC的這則範例會有XSS資安漏洞，建議 ckeditor 加上類似 bbcode + Rails嚴謹的過濾機制
  - XSS
    - [Prevent XSS "on" Attribute Attacks in CKEditor 3.x](https://davidwalsh.name/prevent-xss-ckeditor)
    - [Frontend security and Cross-Site Scripting (XSS) for Ruby on Rails developers · molily](http://molily.de/xss/)
  - bbcode
    - [Rails 下的 form method 技法 - Rails - Rails Fun!! Ruby & Rails 中文論壇](http://railsfun.tw/t/rails-form-method/121)
    - [JokerCatz/bbcoder - GitHub](https://github.com/JokerCatz/bbcoder)
    - [BBCode Editing - CKEditor 4 Documentation](http://docs.ckeditor.com/#!/guide/dev_bbcode)
    - [comment 5：新手求救，關於view 中的 HTML tag - 求救 - Rails Fun!! Ruby & Rails 中文論壇](http://railsfun.tw/t/view-html-tag/327/5)
- 把前端後端分清楚，前端不用gem裝
  - [comment 3：新手求救，關於view 中的 HTML tag - 求救 - Rails Fun!! Ruby & Rails 中文論壇](http://railsfun.tw/t/view-html-tag/327/3)
