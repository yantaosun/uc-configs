# uc-configs
uc project some configs

第三方登录

回调地址统一为：
       http://uc-gateway.61zrzr.com/uc-moudle-user/login/callback/{git,qq,wx,wb}

微博：
App Key：3271903632
App Secret：9826518dc28e058a0e4b43318289dffb
授权成功回调：
http://uc-gateway.61zrzr.com/uc-moudle-user/login/callback/weibo
取消授权回调：
http://uc-gateway.61zrzr.com/uc-moudle-user/login/callback/unauth/weibo
返回值：
id	int64	用户UID
idstr	string	字符串型的用户UID
screen_name	string	用户昵称
name	string	友好显示名称
province	int	用户所在省级ID
city	int	用户所在城市ID
location	string	用户所在地
description	string	用户个人描述
url	string	用户博客地址
profile_image_url	string	用户头像地址（中图），50×50像素
profile_url	string	用户的微博统一URL地址
domain	string	用户的个性化域名
weihao	string	用户的微号
gender	string	性别，m：男、f：女、n：未知
followers_count	int	粉丝数
friends_count	int	关注数
statuses_count	int	微博数
favourites_count	int	收藏数
created_at	string	用户创建（注册）时间
following	boolean	暂未支持
allow_all_act_msg	boolean	是否允许所有人给我发私信，true：是，false：否
geo_enabled	boolean	是否允许标识用户的地理位置，true：是，false：否
verified	boolean	是否是微博认证用户，即加V用户，true：是，false：否
verified_type	int	暂未支持
remark	string	用户备注信息，只有在查询用户关系时才返回此字段
status	object	用户的最近一条微博信息字段 详细
allow_all_comment	boolean	是否允许所有人对我的微博进行评论，true：是，false：否
avatar_large	string	用户头像地址（大图），180×180像素
avatar_hd	string	用户头像地址（高清），高清头像原图
verified_reason	string	认证原因
follow_me	boolean	该用户是否关注当前登录用户，true：是，false：否
online_status	int	用户的在线状态，0：不在线、1：在线
bi_followers_count	int	用户的互粉数
lang	string	用户当前的语言版本，zh-cn：简体中文，zh-tw：繁体中文，en：英语


Github：
Client ID:7c68c5adec251f6b23da
Client Secret:5acfa7743f82ca7ad402b78a72cff64847987d6f
授权成功回调:
http://uc-gateway.61zrzr.com/uc-moudle-user/login/callback/github
返回值：
{
    "login": "Diamondtest",
    "id": 28478049,
    "avatar_url": "https://avatars0.githubusercontent.com/u/28478049?v=3",
    "gravatar_id": "",
    "url": "https://api.github.com/users/Diamondtest",
    "html_url": "https://github.com/Diamondtest",
    "followers_url": "https://api.github.com/users/Diamondtest/followers",
    "following_url": "https://api.github.com/users/Diamondtest/following{/other_user}",
    "gists_url": "https://api.github.com/users/Diamondtest/gists{/gist_id}",
    "starred_url": "https://api.github.com/users/Diamondtest/starred{/owner}{/repo}",
    "subscriptions_url": "https://api.github.com/users/Diamondtest/subscriptions",
    "organizations_url": "https://api.github.com/users/Diamondtest/orgs",
    "repos_url": "https://api.github.com/users/Diamondtest/repos",
    "events_url": "https://api.github.com/users/Diamondtest/events{/privacy}",
    "received_events_url": "https://api.github.com/users/Diamondtest/received_events",
    "type": "User",
    "site_admin": false,
    "name": null,
    "company": null,
    "blog": "",
    "location": null,
    "email": null,
    "hireable": null,
    "bio": null,
    "public_repos": 0,
    "public_gists": 0,
    "followers": 0,
    "following": 0,
    "created_at": "2017-05-06T08:08:09Z",
    "updated_at": "2017-05-06T08:16:22Z"
}

微信：
返回值：
{   
  "openid":" OPENID",
  "nickname": NICKNAME,
  "sex":"1",
  "province":"PROVINCE",
  "city":"CITY",
  "country":"COUNTRY",
  "headimgurl":       "",
  "privilege":[ "PRIVILEGE1" "PRIVILEGE2"     ],
  "unionid": "o6_bmasdasdsad6_2sgVt7hMZOPfL"
}
