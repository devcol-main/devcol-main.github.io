---
layout: single
date: 2023-11-16
last_modified_at: 2023-11-16
categories:
  - Blog
tags: [Blog, Tutorial]
toc: true
toc_label: Table of Contents
toc_icon: cogs
toc_sticky: true

classes: wide

read_time: true
show_date: true
---

# Heading 1: Things I did
**All** add it in before any notes

## Details added

no title
layout: single

categories:
- Blog

tags: 
- [Blog, Jekyll, GitHub, GitHub Pages]

toc: true
toc_label: Table of Contents
toc_icon: "cogs"
toc_sticky: true

classes: wide

read_time: false
show_date: true

date: 2023-11-16
last_modified_at: 2023-11-16

# How is it work
lets see

# Paragraph
This post has been updated and should show a modified date if used in a layout.

All children, except one, grow up. They soon know that they will grow up, and the way Wendy knew was this. One day when she was two years old she was playing in a garden, and she plucked another flower and ran with it to her mother. I suppose she must have looked rather delightful, for Mrs. Darling put her hand to her heart and cried, “Oh, why can’t you remain like this for ever!” This was all that passed between them on the subject, but henceforth Wendy knew that she must grow up. You always know after you are two. Two is the beginning of the end.

# Notice
---
When using Kramdown `{: .notice}` can be added after a sentence to assign the `.notice` to the `<p></p>` element.

**Changes in Service:** We just updated our [privacy policy](https://mmistakes.github.io/minimal-mistakes/post%20formats/post-notice/#) here to better service our customers. We recommend reviewing the changes.

**Primary Notice:** Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio. [Praesent libero](https://mmistakes.github.io/minimal-mistakes/post%20formats/post-notice/#). Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.


<div class="notice">Testing
{{ notice-2 | markdownify }}
</div>

---

🌝 **<u>공지 사항</u>** 지각하지 말고 준비물 챙겨오세요!
{: .notice--primary} 

---

<div class="notice--primary" markdown="1">
안에 `코드`도 넣을 수 있다. 아래처럼!
    ```c++
std::cout << "Hello. World! >> std::endl;
    ``` 

- C++ 열심히
- 공부하자
</div>


<div class="notice">
  <h4>Message</h4>
  <p>A basic message.</p>
</div>


```
// This is code block
int a 
```


# Quote
> Only one thing is impossible for God: To find any sense in any copyright law on the planet.

> [Mark Twain](http://www.brainyquote.com/quotes/quotes/m/marktwain163473.html)



<!-- 
* post file name has to be 
yyyy-mm-dd-title.md 
(ex): 2024-01-01-my-posting-title.md

in post file name make sure [no space , no Upper case]
-->

<!-- Must add Features
* post file with correct format
* title & layout
-->

<!-- 
**title** : 포스트의 제목을 큰 따옴표로 적어 준다. 이 title을 적어주지 않으면 .md 파일 이름으로 적어주었던 title 부분이 제목으로 업로드 된다.  

**excerpt** : 포스트 목록에서 보여지는 블로그 소개 글로 들어가는 것 같다.

**ategories** : 이 포스트의 카테고리는 `Blog`로 정했다.  

**tags** : 태그와 카테고리의 차이점은 카테고리는 sub url이 붙는 페이지가 있지만 태그는 없다는 것이다. 카테고리 보다 좀 더 세부적. [] 대괄호 안에서 , 콤마로 구분해주어 여러개의 태그를 이 포스트에 지정해 주었다.  

**toc** : Table of Contents. 포스트의 헤더들만 보여주는 목차를 사용할 것인지의 여부. ture 로 해주면 포스트의 목차가 보이게 된다.

**toc_sticky** : true로 해주면 목차가 스크롤을 따라 움직이게 된다! 스크롤을 내리면 목차도 따라 내려오게 됨. 이 밖에도 이 포스트의 toc_icon, toc_label 도 설정할 수 있다. 나는 따로 디폴트 설정을 바꿨기 때문에 추후 이에 대한 포스트를 올릴 것!

**date** : 글을 처음 작성한 날짜. yyyy-mm-dd 형식으로 작성했다.

**last_modified_at** : 이 글을 수정한 날짜.

https://ansohxxn.github.io/blog/posting/
-->
