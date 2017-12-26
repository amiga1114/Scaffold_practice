# Post 게시판 만들기
---
## 0. routes.rb
- /posts/index => 'posts#index'
- /posts/new => 'posts#new'
- /posts/create => 'posts#create'
- /posts/show/:id => 'posts#show'
- /posts/edit/:id => 'posts#edit'
- /posts/update/:id => 'posts#update'
- /posts/destroy/:id => 'posts#destroy'
## 1. Controller
- index : 모든 포스트를 보여준다.
- new : 새로운 글을 입력 받는다(-> create)
- create : 새로운 글을 DB에 저장한다.
- show : 글 1개를 보여준다.
- edit : 수정될 글을 입력 받는다(-> update)
- update : 글을 수정하여 DB에 반영한다.
- destroy : 글을 지운다.

## 2. Post Model
- title : string
- content : text
