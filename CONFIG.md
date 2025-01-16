
# recordName

> This is the feed's ID which can be letters, numbers, or dashes. Spaces are not allowed. Maximum length is 15 characters.

testing

# displayName

> This is the title of the custom feed. Maximum length is 24 characters.

Testing

# description

> This is the description of the feed.

Testing

# searchTerms

> There are three types of search terms:
>
> - Keywords: Test these in [https://bsky.app/search](https://bsky.app/search). `AND` is implicit, so `cat dog` on one line will require both `cat` and `dog`. You can use quotes as well `"hot dog"`.
> - Users: links such as `https://bsky.app/profile/why.bsky.team` will pull in the user's posts. To include replies and reposts, you can add the following flags: `https://bsky.app/profile/why.bsky.team +replies +reposts`.
> - Pinned posts: links such as `https://bsky.app/profile/saddymayo.bsky.social/post/3jxju2wwap22e` will pin at the top of the feed. One link per line, please.

- https://bsky.app/profile/saddymayo.bsky.social/post/3jxju2wwap22e
- https://bsky.app/profile/seriously.senpai.social/post/3lcsgzrj4522c
- https://bsky.app/profile/seriously.senpai.social/post/3ld2omcye5c2m
- https://bsky.app/profile/seriously.senpai.social/post/3ld35wuipjw22
- https://bsky.app/profile/seriously.senpai.social/post/3ld35yc3ndk2q
- https://bsky.app/profile/seriously.senpai.social/post/3ld5h6xbs3k2z
- https://bsky.app/profile/seriously.senpai.social/post/3ld7nj3gwtc2i
- https://bsky.app/profile/seriously.senpai.social/post/3ldd3xiafoc2y
- https://bsky.app/profile/memoriavn.bsky.social/post/3ldyh76aacs2l
- https://bsky.app/profile/cinnamyon.bsky.social/post/3le32fsqq5c24
- https://bsky.app/profile/color-les.bsky.social/post/3le2xjqqxu22c
- https://bsky.app/profile/4nokivn.bsky.social/post/3le2xvz55pc2q
- https://bsky.app/profile/seriously.senpai.social/post/3le3jrudasc2r
- https://bsky.app/profile/seriously.senpai.social/post/3legamrpcs225
- https://bsky.app/profile/seriously.senpai.social/post/3lekbjtyy7k2r
- https://bsky.app/profile/cinnamyon.bsky.social/post/3lemopdi3ek2f
- https://bsky.app/profile/seriously.senpai.social/post/3letqfaleo22t
- https://bsky.app/profile/seriously.senpai.social/post/3lewgnxbhpc2p
- https://bsky.app/profile/seriously.senpai.social/post/3leyjnobtfk2b
- https://bsky.app/profile/seriously.senpai.social/post/3lezlxkjlg22w
- https://bsky.app/profile/seriously.senpai.social/post/3lf6g3f4avs2y
- https://bsky.app/profile/seriously.senpai.social/post/3lf6hukdbys2c
- https://bsky.app/profile/seriously.senpai.social/post/3lf6hxw7wes2c
- https://bsky.app/profile/seriously.senpai.social/post/3lf6ldkbdkc2c
- https://bsky.app/profile/seriously.senpai.social/post/3lf6kprlnak2c
- https://bsky.app/profile/seriously.senpai.social/post/3lf6z3c67i22i
- https://bsky.app/profile/seriously.senpai.social/post/3lfb4dtr4is2a
- https://bsky.app/profile/seriously.senpai.social/post/3lfb4tlpjgc2a
- https://bsky.app/profile/seriously.senpai.social/post/3lfb5iwwkmc26
- https://bsky.app/profile/seriously.senpai.social/post/3lfb7utz7hs23
- https://bsky.app/profile/seriously.senpai.social/post/3lfcv32z67c2z
- https://bsky.app/profile/seriously.senpai.social/post/3lfdo5l34222k
- https://bsky.app/profile/seriously.senpai.social/post/3lfdri552f22o
- https://bsky.app/profile/seriously.senpai.social/post/3lfdu2tpoxs2o
- https://bsky.app/profile/seriously.senpai.social/post/3lfdu5x4cbc2k
- https://bsky.app/profile/seriously.senpai.social/post/3lfdw2vbqus2w
- https://bsky.app/profile/seriously.senpai.social/post/3lfecwjivd22v
- https://bsky.app/profile/seriously.senpai.social/post/3lffldtqnzc2m
- https://bsky.app/profile/seriously.senpai.social/post/3lffvambplk26
- https://bsky.app/profile/seriously.senpai.social/post/3lfg53wuf2k2g
- https://bsky.app/profile/seriously.senpai.social/post/3lfgevry43c2x
- https://bsky.app/profile/seriously.senpai.social/post/3lfggmfvtxk24
- https://bsky.app/profile/seriously.senpai.social/post/3lfggvoghpc24
- https://bsky.app/profile/seriously.senpai.social/post/3lfghb6zm222l
- https://bsky.app/profile/seriously.senpai.social/post/3lfgipnk6es2g
- https://bsky.app/profile/seriously.senpai.social/post/3lfgjm7g4222j
- https://bsky.app/profile/seriously.senpai.social/post/3lfgjuwnojc2j
- https://bsky.app/profile/seriously.senpai.social/post/3lfgkrtewgs2j
- https://bsky.app/profile/seriously.senpai.social/post/3lfgx3gqoos27
- https://bsky.app/profile/seriously.senpai.social/post/3lfhrk22hr22n
- https://bsky.app/profile/seriously.senpai.social/post/3lfsfdujg622v
- https://bsky.app/profile/seriously.senpai.social/post/3lfsiduyf722z

# denyList

> Deny list will exclude any results from a given user. You can provide the username or DID.
>
> - did:plc:1234
> - @spamspamspam.bsky.social

# safeMode

> Safe mode limits the total number of API calls coming from Cloudflare.
>
> Set to `false` if you have higher limits via a paid Cloudflare plan.

true

# avatar

> This must link to an image (PNG or JPEG) in the same directory as this CONFIG.md. It doesn't have to be called `avatar.png`, but just be sure this CONFIG.md points to the correct file.

![](avatar.png)
