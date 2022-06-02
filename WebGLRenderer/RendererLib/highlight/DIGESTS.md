## Subresource Integrity

If you are loading Highlight.js via CDN you may wish to use [Subresource Integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) to guarantee that you are using a legimitate build of the library.

To do this you simply need to add the `integrity` attribute for each JavaScript file you download via CDN. These digests are used by the browser to confirm the files downloaded have not been modified.

```html
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.5.1/highlight.min.js"
  integrity="sha384-O7WazgbtR7pxbt/bwpfLX6f0u4ab0t/6eb5RZxYWpDTztIepFUbJldTm8zCJK9LZ"></script>
<!-- including any other grammars you might need to load -->
<script
  src="//cdnjs.cloudflare.com/ajax/libs/highlight.js/11.5.1/languages/go.min.js"
  integrity="sha384-Qmq2J+gCyGClvZHRfl1kFI5O2OLn4OGiWfIFt7RKvnjrQu8Mqol/Zv8AkYMoZ1bY"></script>
```

The full list of digests for every file can be found below.

### Digests

```
sha384-O7WazgbtR7pxbt/bwpfLX6f0u4ab0t/6eb5RZxYWpDTztIepFUbJldTm8zCJK9LZ highlight.min.js
sha384-pTSgwePVvEUcPC/BBwyb5uHf7EuaiNeH6oRzGCVVstyr2pkdhcNngWuarp6R2ZsZ highlight.js
sha384-w8EkDa4C/OvzMW1ZmQ86lsdcYqTNTH4AuPrfPymToHN21yw/OT1P0ST1CuOgs+df es/highlight.min.js
sha384-MgYZpKDuEBLNj2wyIYIR8joFR6arDeJV6qmJ7ep5uw+WfrAdnjJYNSwdepdziNhm es/highlight.js
sha384-w8EkDa4C/OvzMW1ZmQ86lsdcYqTNTH4AuPrfPymToHN21yw/OT1P0ST1CuOgs+df es/core.min.js
sha384-MgYZpKDuEBLNj2wyIYIR8joFR6arDeJV6qmJ7ep5uw+WfrAdnjJYNSwdepdziNhm es/core.js
sha384-EdGuNLd9UpSoe3pHqSdj044S99TGoEgd2nW7unYZrVdNapSBOyfYOjESj/+gESUj languages/abnf.min.js
sha384-fXj12cXxwF9ZJlkoBHKpE5JaVbPMEGbBhPL50QSvmk8xOkduK5dScDkrWgput87k languages/accesslog.min.js
sha384-y8v7fgWJob1jxK5gRzEaXSEd+UL7wCKaSUFVElzBM0cqiwHxOqPkWswByes/+DMp languages/actionscript.min.js
sha384-2P4yL7/hEz5UsQbPqHySDisJOn9mR0PPcVWfNw+PUqcy2AqnjZNguVggesov+fev languages/ada.min.js
sha384-jfYsPVafWkezpmGKPy9UWyNY0QcxAruX/NerHn7iusD8lDB+Dgd5c4E09kx8H6JT languages/angelscript.min.js
sha384-yGVYOfVn5p/GaTvP1xMAp7hameki6chJOGHYOvZHYLI5unbBHUtW2pRHzc5jffRa languages/apache.min.js
sha384-4GlCAqTUkzKal7YAvMh76kKcI2atiylV5N4SLLM4jA4NW36GXwkc+IAtyjtHa5Wx languages/arcade.min.js
sha384-kx9snubDZWj8oYQctuOQ4aNeSSMr+oieuPIDlp7Jc6P2y2KiNi8An133bd9fnH+R languages/armasm.min.js
sha384-pY2ynbqq06t/2WVVJ3yYeduQpi+jeDCkyBS1vgHz21ngSh1TdGNr8Od/heMCnyyo languages/asciidoc.min.js
sha384-ipPMxvUjkrslJOfBELAw5q7DN1AOuTvfbq02nT+ooDaWN+kVemvFE6hTNF//eHJr languages/aspectj.min.js
sha384-irNcSOlwBCRRmMjaYPmLscCxCxr41dAp4xTpHIw6JWYITmzfkpxEq0W6gd7Jjtas languages/autohotkey.min.js
sha384-GJZorAMpM2dX+4IgwCyS4AY0417nVGOzgDyZz1ZDV67KV5nOrr++p6aY0Fgs4ZX3 languages/autoit.min.js
sha384-RhUu5Pz4jDODCA+4kJ7x6157QAVbIcUc45ZWGIroV7dmY2FSYygQky8KQdQxiQFL languages/avrasm.min.js
sha384-V/798XzggdXv5w4j1MlohgUKuXDKj8jlElqPshk1TL0gES2zr8zHsm/0c7riwHND languages/awk.min.js
sha384-2/tABskIOskPvM56msApd3Cgd8l8EwauU0gyD6WP8l9HhGG04LBUrORGWGkJfz3u languages/axapta.min.js
sha384-uwHWvsZ9ldkWQ/Ykngvw6C88NNnluEHSiCYDXbPAoRIhLpUbwoQDOdOlMyKZO3I2 languages/bash.min.js
sha384-bWu5C+MCyy9l3dNtcSzYDN01/IRoUIgMBae523BGxn7/2+VyVcGNVLj3AKsyqI+s languages/bnf.min.js
sha384-3+Iakof2r3BqfzHk7CI32sbgfziXSfLScmBCJp2uluhPyigs2xT7gVv6drswkgzK languages/basic.min.js
sha384-p/AZ9Nl/nFQT1DyoGanphg1PUGB/gtq2bRHP+/htuskeLTo/wiFTqVNErjVhtW1f languages/brainfuck.min.js
sha384-rA4uTzwK3xnVGilVXQRllVy2wXvk2qRMIoONfLkKsPc8czd9UzUELFhpneRIMc85 languages/c.min.js
sha384-5GZR74pOP4tMIi/N8cptuWwCoZNr70URJLopdkGV11icjbLERmNEU6t6q9528fEd languages/cal.min.js
sha384-3qoUH8AeAfie3NwAeeen9UJ76kuD7WFGoZLc3Kmw89fuk4xqlZqfNAoDmwgeQSis languages/capnproto.min.js
sha384-rCtceNo3XYRiFiGkEMbBXfNjNLE3oQdsjp07knrvF+LU5R8YrqAhKG+VhfqGi89u languages/ceylon.min.js
sha384-Mt3NmZXdx6kuDqsm1gCerxBc+5gkYLwYYdYLyF/DB13mSOg3yBhd8a+Y13Rh9Rzj languages/clean.min.js
sha384-DXK6du5er0c7uADTk43WuT0sCdFieP1DwRXHW+3YcMBRfSz6KvGDaaioW76Onp81 languages/clojure-repl.min.js
sha384-NdhIA2xUZM5z6z5nyov8M4/3BPS5xuKcYYv5hsNeamTlmmx9K7JbOjh+pQZJXJVV languages/clojure.min.js
sha384-h9FAKRDT0pK+twxjusK06KqMTAS1rg3aHI7RSixiZotyd1LCU6s897H3sZZHzFHU languages/cmake.min.js
sha384-69g7IJFwApOE3jh0MfLVwkvhxzwVucs9dUuKdU4zilW8sGwrai0nJVErKwcAPIJ1 languages/coq.min.js
sha384-SaZ6yq9+NEuZAV2MBlRZBoNjeEhxm0NeNCWkwSEKDVY7rltilIPkThRJLZc4NjKI languages/cos.min.js
sha384-yZjEhGIjlasnvgGlm98BYXFSRPpyutHtQD97V7MkNG5gAwkxuygIoqtNuJye2o91 languages/cpp.min.js
sha384-GL/L3Y+re3llvVD63ZXGhBcKZM81qR7/zQdnuz9EqLHPy1gsUNRSNtwkHWxvgbxj languages/crmsh.min.js
sha384-65qeBquDMfaZ/pXslGSbp4YdI377Zu88hUkFXkA8PgORMPZ9RjA4QKQb9i1tCEzV languages/crystal.min.js
sha384-lWRBKpzbBzqOW1W4NWDXK7Sjn9cu30Jg7d8NjxNaccEhUVdKefJZJgDFxQl2wBfR languages/csharp.min.js
sha384-RYt/VyApESANZbqDiSTqDfzgy/C8UzTyu/D151BgTQZr1gaqgKzYwF5/7Eiyqeh1 languages/d.min.js
sha384-04/yTZEQK5RIh2vJ7ST78pOgpjuVzxG8cbixRSR+t3FYPbT8wNSg68ZI0sfDlhMj languages/dart.min.js
sha384-m6qCuZ+6dUiTMCWIXIL/WJyZFcRXZ4C7M4yg0MQ3oPKLN6gw6zKJtOHRgHdu8DnP languages/delphi.min.js
sha384-OQdLkL7viF6yI+Kd4v8evkx+rITL3yBKhQt7q2aDXKnJTaQCessuDVa6NfgLq9gE languages/diff.min.js
sha384-OdNNE7/WSHhH7O13Wgwn0Axl1EJtdJhewyDlpihOnqvEH/dW04i6qc7IAh+8NHnV languages/django.min.js
sha384-iA801Pxi5TaUDqD0EcLxqfJcxVwHzQytK85SirpnO/K5lGTxyFoHUvTVGbS0byW2 languages/dns.min.js
sha384-FCLqeKYLTlJ1AuKD6cm52usT8pWcj26jrB7dJ9PMTtQg5OF1Nzc2dzM1a3NtVE3S languages/dockerfile.min.js
sha384-5np5iJbYbeUdMJwy2fpghpirajfhxyrydWaL00+lbewRlhXmJ3X+mQjhWOqF2Gbb languages/dts.min.js
sha384-pniY8CFWd2Ru07lzOuiK4MscOwEvyNjNdnlZJyA80nIAFy3MOaKPLKkOsbIdhFu3 languages/ebnf.min.js
sha384-NcO3Pp5PikfyI/PaiNWTqnTjYsHUz2ghX0N9KKALJNusGCviJQiAJYaYbEh39Bxe languages/dos.min.js
sha384-yzWNbHHEvzja7Y2BPaSzEN/Qm9wEKW4k+tXfozdHo9lSPZhTJYypVYgZzJtEr/a9 languages/dust.min.js
sha384-skyLjlnlPV16eL8VOpLlu/NVCA7iM1V0COfCcEFxCgreuJwsHnkXMSOQU9oLtNka languages/elm.min.js
sha384-P4+h40GKNQsMikb7++DCAPnC4lah28xN7dGwn8KZJCC9tDuu7jKbVwg4uVt+0lnb languages/erb.min.js
sha384-VO3eeQGf8KEV0wplLl31BxTouQgI1YaM7kAGafTvnaRCnK/oVGLrrlcLfaOPy1E9 languages/erlang-repl.min.js
sha384-pJ7c5enFtoglmWohRYsP/j2X9gThTStuSkx1qfqz0Vw9/iW9Qthq6Lo3r2WDhmWY languages/erlang.min.js
sha384-/5Gc1vEX0yyqFMjUVGZhH+7cUr7A40RN392qiS4HsW2bGijud4m4Vnw1+xMbBYgE languages/excel.min.js
sha384-mvSCVgBHQ6Rbudv2YsLtZ8gUu/hTPrpS2+ICXBLWASwFtVP8mjW9DXWE6Kq+ekHu languages/flix.min.js
sha384-H6R1RdS/ZBgkDbDbZJ/iEcVg7/9juPgnf6YD3QOpLueaoTg7oEbyAR67WpFWTQra languages/fix.min.js
sha384-yMkgS3YJa424pSIviT47g6suiyJ8JsY4eHFqyDcEkxdAgHNun55Lz2ec5plVT6n8 languages/fortran.min.js
sha384-a5UByJRqTa4+lDjeve9AhOqIml29/RPfxcaO572tr7glkCfg9ddIL6C+tNx8jBOh languages/gams.min.js
sha384-rU3K27mTd5IVbmYhzbx2xagVFqD8ij4/2lO4RfkLQCyDZo3v1iTUteJwPSjTs3ys languages/gcode.min.js
sha384-CvNGJi+wpbtLkptiLu2Ei0ow6HwP7zMJ+aczbeBFV1AmKDgI6IcESgK0abgZ4Qcu languages/gherkin.min.js
sha384-LbXP9B0F56hJdJjKWO9rug96etys7o2dwntNM6wQgSFjadn4+GRMQVZ9uk6Xrh4d languages/glsl.min.js
sha384-Qmq2J+gCyGClvZHRfl1kFI5O2OLn4OGiWfIFt7RKvnjrQu8Mqol/Zv8AkYMoZ1bY languages/go.min.js
sha384-7xEZmkmTAi855OM22GqU9pL1+Y0ALT8bdOX2ln14/fEmDqzJHyCcB/Fb4xf/3O96 languages/gradle.min.js
sha384-w99Sn+QlRljpT+s+GavEd2FjhJ7j+gJ5JFHmrKjwsUzFmieiIBicfXFh+dIgYoPI languages/graphql.min.js
sha384-YLZCEyT96SljR3fY72+USJ8c54aS5dr4HpUSIvxdK/7n7xkZ0kD0agdm8R2JgysT languages/groovy.min.js
sha384-CuhG1sKM6PzmbpaENgI1euzJFjzcQqVapRBpUL6HS79PBGF3ksknxoeP3HvbzT1m languages/haml.min.js
sha384-bQsRxlDhlkT64TBxtvHrnLUKBPMggiiC/IlsQqPRfiFFgZ07k4ocGJhnebZTbQ6y languages/handlebars.min.js
sha384-ecWU5iFafQZOyLeBLSaEPIeB53smcFd3B7YQuF9yl5Sn1KLMnNszpL9OLm+wSmPj languages/haskell.min.js
sha384-faHAnCLn23cPzHf15C//ZFkuUkZNuVIC9FZNl67JRC5gJ/pHAFdzpBphbTm8kqPN languages/haxe.min.js
sha384-iwSK8x2KhMuVYRZFN77I7+Bbm6xwGBzXG+494rpR6So4E9Nfxt5XdcFA+SHWF2WF languages/hsp.min.js
sha384-OaLQ4qNDPuclIlT5o0+1LX/UgSNq05t3qrDC6VABnRDcjQu8ZFu8BhiqeFBFvP11 languages/http.min.js
sha384-0MJPukqcw62oxcquDBOHAcFXJM7G+rYGgR7xM2pr4wK4+LpnlTVgHxkmOuVFMldE languages/inform7.min.js
sha384-Qu+ajbsViDh1SBE61eJjXUhEIg5EPgi1C5NzV8kiIqYYKeVF7nrNROmah3UDpW5J languages/hy.min.js
sha384-xypowWuZwTR/gDxMHjZYTgyQAxY/cAlvOcxlBfGOHSZknjEtP/fyhEbSEoBOXZTE languages/ini.min.js
sha384-emZONOMOkjfW4my/ZqHJT3trxJAw49Vvy3Uck5qyw1G7ymoDvdrcVEaGxz97f6P1 languages/irpf90.min.js
sha384-b/zfHbiU9h/aWwljCxsFHI74EzLJ32Abn9YJslf6OHYfWb3xX/udIgcmczaujUbh languages/jboss-cli.min.js
sha384-8Io983X8K+ldC3uhqZB4GXwrBywcLTBvSllFu3/xwvtCsuP+A2rJD+125kPdqZ3C languages/json.min.js
sha384-gFhkWaMIZOpNVc1xZk01LKSfKC66D8PrLXY9Oz7Md2dFPe433VSgBZuvyRZN0OTN languages/julia-repl.min.js
sha384-3v6lkkeNVz+bnAIA22166aVNxz/8eqvRK7sMFEHaTd0xE5f08filKLU7DAkCsuyR languages/julia.min.js
sha384-hZq40381g6tgKjcBqsQ1K+2vyCS9x73e7gAAexKmLYfDw0EevMehVwr89cwz9is4 languages/lasso.min.js
sha384-MyI7kAYg98BOFnvUt+DuqW4eoWfsZuoEQFScwu2gr/g1+/GCRsb27GMDqzfBKjCb languages/latex.min.js
sha384-x41E+rBPzf6oQlGxb5gnfHb9CMR/jpIWtST+XdQ1NL7iKehgvuJNU5412BNueR94 languages/ldif.min.js
sha384-nInAnXI/6aaR8vTS8HfHaTm6VEeDGknNPO1ChR8G9s/UOJvJ946SNVfRFhr6zO+Q languages/leaf.min.js
sha384-iwjNvNFplGry0X09QhWRD40/4obLbqJf7ywaXfcAjN+8n4dSXo55KWrvYGWvj0Ol languages/lisp.min.js
sha384-AoC0X/A+jAce/tLVbeiGdr5cHsU3vYvaU8snfT7lusTt68QiLgRAdh8yovWagd2v languages/livecodeserver.min.js
sha384-hxBjJdLhO34esru0SZCcdOe2OQu9KUi6U8cl8eSVgxreV37Nl1/Kbs1uHh5TiITq languages/llvm.min.js
sha384-a6tclFNNxPjOaWl4I5yJjC2qVaEq/fjM3s5iMPFqV6FEDkEcwZkJy3+5QoGr14h2 languages/applescript.min.js
sha384-udRg3K3xAVo8dbZTt/d8UavwGQzW6VIfp0laHR9R3zl5ERib00qFPoi57/lSZlTG languages/lua.min.js
sha384-hILiRldReFZl7qr59ph9y4tCRURx1/3wcuIk51Dmpso9YU9O91ohph7d/rrhDI3w languages/makefile.min.js
sha384-NvWRna7ZJrk3OVKcIyqdNxL1AAyuFe7HZEjc7BRtONEilfVpKzhhe7YY7ioXL9N1 languages/matlab.min.js
sha384-0CU1BZEWK3sZhc3volwjCeoLS+zW/YJGsKqVVwjxviFbVjoZgRmCzuH06n5GHGls languages/markdown.min.js
sha384-1h2VlcnpeXW1HJucuRI/aDjiq3vynhwP1ayjbUqeoSykQuCF4yWeQsjdvQm0Wz6I languages/mercury.min.js
sha384-IN2ZGpnCZJzfTZpBlxbSoKNIaXKsF1VTdF9wm9H2/zyZsJ6e5eZILFI6E/dXZbKx languages/mipsasm.min.js
sha384-3f2UCRid0AGnLCb4+xvA+869AUGtAUviveK26UOjmKT7ckrNrvz2b8A/R5EiW7sx languages/mizar.min.js
sha384-cTMiovpRLU+v38lNBFgQLqQJcQidLIMbTAH8xIEj3DIrQYwH4Das2np5IK8Ox6nC languages/mojolicious.min.js
sha384-dz1hoMZCEpp5BC3l03WPdr2y+tgAy/x5D7YRH52OrwtNmyAYtKa7jBl1T0+uh8h3 languages/monkey.min.js
sha384-jj62RbXd+ivgxAff3KMnAz5JXdXOf8gJSgMMlqe5YCho88i7qAP0Zu4a1PaozKHE languages/moonscript.min.js
sha384-/1QWS6nGdCDIawDH5CRcv5/vButkQRhdfDTCmWnyTEEZ+U3tcB28nVUOuU27aXkH languages/n1ql.min.js
sha384-QyFt0fY1H/v9jNGG25aW9sIuD0Z0qCyxohGIINzEl7I17Q+JUj+AmBydrb7XrCP+ languages/dsconfig.min.js
sha384-x4s2XNKOuAljJrZJ7bNQL8Vrkn/BIp1TTQVa7OzAZ56KOeaujRuZjmpP+DZyweLr languages/nestedtext.min.js
sha384-nMlmqYckPO/e9iv8lzLXU1TrZshg0jia4MZRsD2HnHpEt7O86IoQuBLjpLtUUJFA languages/nginx.min.js
sha384-wW/J/M/dv8TN4DcL805T0BSejL3bfH0fw6UmZ2qhcF2f/MImO9tvjwOYALq9vT5a languages/nix.min.js
sha384-6adPN+iESawiww8FczDTGI7tKdqQxf/XZY8al9XqRR6yEzqatcuaMe02tjxQInFr languages/csp.min.js
sha384-VYfHS7n7Vbzrwzf1fEDd92M/ObYTL6BZGKw5xQSIWvQA3QB2maPbfsVAzGZaf5je languages/node-repl.min.js
sha384-c26TM+YI3d4SKUhPFhHkDOTOKw1kpHmOH1K6HlhvYC8sYihgePUpJZF/TVy+2+pg languages/ocaml.min.js
sha384-cQVPsz+Xn7e1o6hsfQwlzThdbHRqS3HfuMYoi+QXxrcctukeZDB3rrktIGPLV6qe languages/openscad.min.js
sha384-T+VFNolBXl7ivAsMxIZ0gKAGQ47H4PjRZZF77mRmbiiASJ5U6zQi1TD4/2yoGIlH languages/oxygene.min.js
sha384-g3GEo4QMnOP5v5gRpBUHyXEPqMV87p7wLt7q3XJKe0TOqPmtSLMDTuoP3CibbWma languages/objectivec.min.js
sha384-fnoG3hZmpYHk51WauvuJFugP0TFP4kuuxIE0AnO6ERbzzrVolrsHR37k3lca02Q+ languages/parser3.min.js
sha384-xpQG97MQ0Qhe8h+rNyncx+FkVooaqP8TteUcSpaBUq3hlU1GoZc18sTJMJBB9t3r languages/perl.min.js
sha384-pla3P9iGoEo9TTDs/iLhkk3mvQIL6UEZty1aKTze08ZIKIF5f/bOXS3MVZ4uIT+f languages/pf.min.js
sha384-KiWghS5BF9OWw1z8qoQBJh00Bn/8ZD5FVzXTgH7q+BNpDxSELVJ4YIc22x9CXkf1 languages/php-template.min.js
sha384-8GbNdxczGSZqXJRjRnPLKLk3p1AkBarmgt+CHkQWNjMndfmqeaOjVP0+LNj1G+Wb languages/php.min.js
sha384-4x72Sdkxo4RGHTAeovGYbcIXst2MfDWenGWbAdmwI4dpEnwuDA/T1448YaJPcSLp languages/plaintext.min.js
sha384-VHMYmNMpNUwfvYrkUU8eF7tMFEZVz/A8M8t9eCNkPXkxw/E7FTDRdqLAaHdMdt4l languages/pony.min.js
sha384-5dY/Kkeznu4IIDRQyT6jL9e1XwSy39f1/sqYLFifcz2CfKQe9AunCsb7lBEeMh+f languages/powershell.min.js
sha384-8523hTp/rMNZmS5HlAvhf8b5oNrAEJFqOS+PJyP/+ozhkRzCsbieGbWUIcwWpJg9 languages/processing.min.js
sha384-uwsO6stomSmvuR+xvNl/nLstpYlJcUe/s62n3Z6h48oqVe17PB0ApS/pkMoToUhK languages/profile.min.js
sha384-N4jCEWWYO3TYrNF0da/Tam6J2y5SAbphfFXzQKfMWKH90T0f6qNZ5zlSCyQuwGBw languages/prolog.min.js
sha384-ut8aBKSzRXur0gBHj+rUcoTxMnVDZZi+Hk6dwxlHkfNX/rikd5lF2dyrCGK0bsJ3 languages/properties.min.js
sha384-PrKq1vnf1LJYk5b2+qbCcGv36i3437RiJvP1hDle2bhprlciBaf7eikYToWnc4QL languages/protobuf.min.js
sha384-g3ameMZ/MorK1G+UT9Nr41NS2wYSRbtoTtrGymwvGAcgydGQS8jcPWXbsC2QK+L7 languages/purebasic.min.js
sha384-/eeD8XnKwQdy32y7GNwmpAq1l4W5NCMGQ/IG9mFUZ6UJ+SVRJP+9J49Sbs7K+Jnw languages/python-repl.min.js
sha384-d8fQAFbauvo6oD6GB708DpKblA3gg0tR6lhJf8D1plKP/xEPsv6+yFms/bAEZPHI languages/puppet.min.js
sha384-WbLehv0TTfkZF2TZ8dC5P3wFVPKGBjbMBecLbDog0xqhrPcDJh8SZTpysyITQoSU languages/python.min.js
sha384-7VIP/YbKep0+AYP9PU2lFSBSsDDdL69SpsuQKCHWUf+1k+r6McklS/RSiENsd4xF languages/qml.min.js
sha384-B3mOkTQffKiO7e0AK8O6i0MQEsUEyYVJWcI6NlHtVs08lmWoGqN2RhnXgoLNcxTr languages/q.min.js
sha384-XoB3OzmA9eUW6JTQN1TlDEFBbsM0H9HXBZh9wq6TkzEjqGKDReCBwKqzGZCYGm2/ languages/r.min.js
sha384-tLkQ7og2+OMpsieTZBUS4wu03qrk2/YSknkdtP7OmncJnWjdCSjkYjG/cIdinuX/ languages/rib.min.js
sha384-j7hgCYqSWqjpTEbi1CwUIzrABkHfDz98Cu4eVPHhecS7KgrQjq+qg8EY0JrJ1rB+ languages/reasonml.min.js
sha384-fa1NWUOxhV+iLme7Kb3LLNRO2asN2lRaNj6nZ6ZKe4JTNllWdxr8pHwZguD20tqK languages/roboconf.min.js
sha384-g5XVrYZx3SYl329hnUq9lapKHcD2Ri1HKk6S83JHcjz+FE6PLg4sIWboPmEgx1cM languages/routeros.min.js
sha384-ZZ2pgVJl3U7Hb95cK4MeykKekLimSkdVRiALLUsXxy1ENU7FC1z2AcqZSwfPM2dy languages/rsl.min.js
sha384-dMTkER7ed1JL3Pzhij+nxAG1K2rHihgARjk+Ea1X7TaiOUz2WoZOmcKrlWvpO16l languages/ruby.min.js
sha384-xLBcguarhFcPSiTxwPCo0G0LJrpAWlPgpmplPstYL2ii9RY1fDSBbiar58QNsyec languages/ruleslanguage.min.js
sha384-xMPxFB6LvDzDil05RkYrCQfiBNGiCkFEmdUjzmskIOVUH6Aj3WbDTY35k+w23RVw languages/rust.min.js
sha384-WdnswpLGqXUOkRREuxV+Dq278UI3buzoTH5b2YAOStY7wDmcLEPLlWZj4MFHwdk+ languages/sas.min.js
sha384-M3Tqqq5ItnsV72ZpY1FlgifvT8me9Oo7/u0HQROjMoP6phSfniyKGBba574vxn3V languages/scheme.min.js
sha384-6mk+L1WnMqbVJ9EJyBkLMfokg/c2UDACEjvkDggNcR8G4SAMig7HeJ3hF7r/u8OF languages/scala.min.js
sha384-TIQugJkXZjZCz6dKLxuZUviToHMVWijj8DsduRmPqYN4quyFZ947AhoyEF6+knsN languages/scilab.min.js
sha384-q2bnxf1c3FHa1Z0vnZEYJAjT8MHrtkkxke3F+HI9GBM1stEzVzcw/0Wz3cVU6FEm languages/shell.min.js
sha384-fS4Jea4k0ma1LL5qLEcAVwBzPRtG/oiMHkUQwyhln3jCWOAIe/QoL3pqx9UUv358 languages/smali.min.js
sha384-8qEYQlVeB7SOBln5FlzeSGXl3EatY4O4r4ewERKMYIbP6NMWUrt5Bxpmu9Govkk2 languages/smalltalk.min.js
sha384-Ogt21DsHAEOpNDtJGRM/SranZd/fsUdK4TnN2uDQQRKe3C5sbKqn2zkboKPf0w2N languages/sml.min.js
sha384-S6V98GfArIdagidFhYlGmkHD2dg6WXMvOppr0WNf+tjQK+JgjtRrDx4CkrHdPmF6 languages/stan.min.js
sha384-7qYYZDS2Y6N7Qy7AyNMFoQQsxEQKuBB8xZMnvfZVCDMLy8oGH5xEsmwF/sXMS110 languages/sql.min.js
sha384-FJodM86bI6fMLnfE3ywHet4rKvwXu0vnpZGtidAehMIOrWbJRBR5VbpvwqqbHaDY languages/step21.min.js
sha384-FGtOB09uyeZxNeZ6sJ6Mibss/V+m9Oy9VQyjJy1egseN+XWRh4NOZjT0W19lKmUF languages/subunit.min.js
sha384-6OqwROaqV1FOoImSMIyHGcalDI70UqNszNS/LX+nXvVAcZ/aAySX1NZKWQBTBqez languages/taggerscript.min.js
sha384-IyHl96iC2gi4q0MwyTUOyw5wspTWKu4vsU7nWU4Ui9hn49d+J1Pk7CcOrhxfsHUe languages/tap.min.js
sha384-uA1zvWoYGWx5jKyDEufPPiFg5Bj8FIdLOB3AltqCFFCr5e2F2wK9W/eMnwhVDHPv languages/tcl.min.js
sha384-2kxHmPY2uWWLUTgRXzjO4kI/ny4WSIz+pcgIVaRdEWkXh7GFNDu8tNDIB6ehOwYc languages/thrift.min.js
sha384-OZS7wHdS+UUmxmT0hYGspv7wcbxXIyyeTee1WAVdpNgaPegTvo9zQWYGnLm8Enfn languages/tp.min.js
sha384-aEqmgAJzgzj2SIuFMWinyzwwv0dWwOSDfdLzfLvxsldPl4pdu6XQTPjf/Y10cd4J languages/nim.min.js
sha384-bCPOuads+gb6vwl/xMVeshdguJwI+ZwM4+Xjd/MzJ0q2BHVGyCBnFKqA9XGpd6g0 languages/twig.min.js
sha384-nLk27MlvhqWT2iDocu729a4KFucaLx33whoDs5kIRmu6Hj1QMyMR5dKrUNp+0h08 languages/vala.min.js
sha384-EN9fHTs/Ki0RX5/vXR4Y2Qb0XnV2+j2GVj86nencgtJYbNlNanf3ogcbPVkgFKBf languages/vbnet.min.js
sha384-W9uVWmc1x84IT7JwiEcZ0xuEnvNV/69sblmjjkYVMilTdsXmoE+nb5jdrPlRleTV languages/vbscript-html.min.js
sha384-xKvHi9TnRWV9qYA/uV8tN82o4HjIRR8BWrE0wZhuXM2Oz9P5WBlDHGPQd0cehJUj languages/vbscript.min.js
sha384-buPl7TxRyxlegONS5riWANG2Jf4XOW7QmcEI8ybkpwKkqUXcj4gvQekcw7v7UBka languages/verilog.min.js
sha384-1d/d6BbndVg5G0+9NOWu4FZmkMCxSHZds0EHdBWWCARMooLkUhNZT6qXJzowUGw7 languages/vhdl.min.js
sha384-V7Xe3N2lImEhYa9USim3UPhhT4rA21Ms5Z45xOz0B98mN0zFEul2GSFxG3/WaWP6 languages/wasm.min.js
sha384-RK3QlBLKl9s/Thq3ykq5fvjObjkIFTtLYOLG+/GrJ+Ue5/pyOGsYkX92J4uXSpPg languages/wren.min.js
sha384-jWyJEtolrQdVtPVPzPCDoDApq2Wv5CADQBuaR4D7WXxPnWsU0bEHUs/qnOhC3d8y languages/vim.min.js
sha384-/nwDOZfuVwk5dHPZY8hYp1C4IzhVFo+S9YJX8tbtUKZfUMF1xeedCHbXMV9Agnud languages/xl.min.js
sha384-Bx3YQ9lddbUNgGiEkDbk373yz7DG7F79t+z9kBEZfpBd2gDIG5XMotMlOWcTwkpr languages/xquery.min.js
sha384-rzvqYT6ly8R/KXwjjBMhL+Yah9/VShEvAX+GFlKhpjJoS+NEYpnQ99v0K1GUDbNW languages/xml.min.js
sha384-vLBVpaJcrTRsLBHhkvU9neJTiLqRgYWBnEg3o4eLgTKw1+hWbSr/QaNuSB9XWftA languages/yaml.min.js
sha384-J1u/OWzFRcdYv8gAJvexyMJjtAjhjGY0EtGnstnd69yRsQYV/s2Ad928oAzH9R0D languages/elixir.min.js
sha384-jP0TLMIukWqPj4ZVTcyii5iF/CVqdtlKikssR5J+gyW70U0jNbyT6VZSmvr2ZIi+ languages/zephir.min.js
sha384-EekwE+OW2Vcwd/dcGPgT30RbYHqiaUyKzI+3PalSu2qyBeDlr6Sq7/bD67o5x59o languages/lsl.min.js
sha384-nPOqI8ZxDN/Ai5KVRmt9aJW1+TpEUDn7mDzBZVM083RJ+CB0tB6MkPmbTgd+8AXd languages/golo.min.js
sha384-y+xYjVQn6aSTpgSCimrSMsDL6hHF+GFA+mhO9S93hBAcYR5iOseOF3Q3vOOAOqER languages/gauss.min.js
sha384-8IQS8E4Qt74pmLSIeIGx5r0qUib3E+7kT41OX1aV5lCTzbazMOf2WkiKdBbAP06j languages/mel.min.js
sha384-BAdb7J6BjimuyfCUDUm13CWjD0pEEjRrY+Tj4wnu8tFruj+KaPTL115bHA8HTqFU languages/pgsql.min.js
sha384-a9RZsrXCCoeKm2nSxxbkGIDeP733bJzdT/iLFSJiiI/r0vIO1ui4PQLE5oqoQvIY languages/stata.min.js
sha384-7Fc1oBjcMxuxQLtOqelyF1TvQtAoK0XEBuh50E6sgkOYUbOSevYc9AP1Tn8Dho+9 languages/x86asm.min.js
sha384-Nk4USo/dirbZrj2f5u7Sb6ETOfpP2uKbzVhqSzyEUQcmw5uDr7SbrZzpC8ZFbytP languages/maxima.min.js
sha384-iwRH4zWEq9JWlxXQUcnWj+RWP5ZduGpwT9ePfQa7DROBa0R16k2BolV4t1fGnmEL es/languages/abnf.min.js
sha384-FbPXUvSizmBmzACWt+rECLgE3Agp9agkERKHVWoNplLlXChUOeVm/xjykioeCpGQ es/languages/accesslog.min.js
sha384-ztCJLbxxrc/MDs6KwVJbRcL7WcGwMOTYeAd6/Am1ebk3kzals+A9YQHko77CAGIq languages/1c.min.js
sha384-729Zx7KxvwJJ/bqJrJaGTvjyrCfGVrTU8KwsP7TjVVrXXbPpWwiJUgViqOwU64ou es/languages/actionscript.min.js
sha384-rU4pyLl+JBO7yx6xpsWGDiRkZhw8aD9oP1+4GyJn59XeeYm4Ln5QOGFF27N2zRBW es/languages/ada.min.js
sha384-7/EI3ZAlnOOah9GnIV9zdBt9eEOUzt9Eo5pz7+hq1KHlo3cCGiu6qrgx/DTQABzB es/languages/angelscript.min.js
sha384-37QGtZiY1BBXPArT5NobSDnxgHrl6KVdt7DCxmWfihOZrmgFBEIvQtvQbyS7Mzxu es/languages/apache.min.js
sha384-X1G8GNYcAueSB5N1/hfgcqws2qJc+2wVQq0K46QS41qvaNYZXTObBUn94GTBWfI4 es/languages/arcade.min.js
sha384-SNQE5zyvpfsHmn9sIgQj1NVLEHMWnhGoyG69IyWXjKdXkWq0oglYGEOoZP8AbpjO es/languages/armasm.min.js
sha384-oTmIScyzaJieaJ5+awsbL9sYZdQiFnU4ktF0E8UWpeezZeE5YjjUxOM+rtrbLxAG es/languages/asciidoc.min.js
sha384-eJR472dL7iAIxVAIammm2bn7qFbcSva/Vqi3k6ZRTeeZvjz3VQwTNyQ/Jp5lLLzi es/languages/aspectj.min.js
sha384-QiatiTPE3wYL68LHDfbmv/u6VCp+Ed8K2Ess9ey7EyP9NSv/stLaCRg6ROjCpF26 es/languages/autohotkey.min.js
sha384-zEhwvlZ+mc5rb5fbqgcC8qrRM8e3ZxzbEefqH3RBhd3WbWW7w1OcU7fjQrUGpFln es/languages/autoit.min.js
sha384-Dj/IQbSAuPOtDczy/cIg/sO5yTxavAClN74nbMesmo8WHPc981CbCkn58VB3JK04 es/languages/avrasm.min.js
sha384-5O4Vfxz1Bb4zKbEz9ii6yR//CPp4GAr3FBQI/C4hzfCHtCyiRgFk8+Kiae6KRk0r es/languages/awk.min.js
sha384-Pk1LOa1Sscf9MkPbhLjAsXHjKh26VzdIkBbgOBjzto8EwxJx+9AOLDGteWpur/I1 es/languages/axapta.min.js
sha384-EYx+p7/M/QmZZFufcJ7ziOc2hYij9hlrksA5k77m0M4HGMH/rk2B55HhCqvayTNl es/languages/bash.min.js
sha384-BfQWAw58jww+gS+05ZiNeagcaJdSGJnMXIaiGl0etCQcCaOZIo4oIO1Vctm0Fj2M es/languages/bnf.min.js
sha384-BKk+AOXHbZ+fJOtb80/JP446Q7eYh/7Bxiq7p50st6202/meQgU/I9+0sCHSs0as es/languages/basic.min.js
sha384-l+Cvx9POF9ORBdI9m77CkMaDBV4gbAhwmleo/cUxUMM3x/HGX2kBMftuio8AnXxI es/languages/brainfuck.min.js
sha384-arkkD1qm2l8ue0UV5Y2mnLUoI6ZEYhwdiuYn1Rx1qeIOGQWIvjLFys2tZKlGJ3+S es/languages/c.min.js
sha384-7tPiGuwiP+zoX/Cn29OaLIWZDSVkPBVmgUYUJhHx0IzUEYhxGuRHfeFp6iCw04Sa es/languages/cal.min.js
sha384-Yu/PYJsY3upsKV3cq42C8OGorK+kKYK39dsH/Oe6Si+0BbBv738iUU51rKcwkD5w es/languages/capnproto.min.js
sha384-PaBRCdBHiXOjN0iFxVjHL+3zT9aXEHQmte/Vb+IMhRYjuusoaEYvgI5m+e/WUr1c es/languages/ceylon.min.js
sha384-3nHzmR3qE8NZWy2NrQkyT2VBeyz0j+yMVobls6VPwbttx2BWITvMjOIPqfdo9yzK es/languages/clean.min.js
sha384-efFOb+MobMJ3FDR8BBIPd+ZPjUnRzL+W9hYfv4BgICgrbjhOljikJuNFVdzjjuxc es/languages/clojure-repl.min.js
sha384-8MxmajTDcVcCU8FI0F855tS1DavOdpcQW3wK+eusHMKVQCLKTtaNyWip0BnJ012+ es/languages/clojure.min.js
sha384-jdGvnO7rl/vH/0QwdWWTdaKt5llp/MwivWaEaVOg3bJMZrl8exdvmHsiBj29Ey8U es/languages/cmake.min.js
sha384-7edyFyhfzeP9DP/JkAMbPwVmaBNWd/5c8pVMWZvXCj6CM3Wkj/wfa3pKXLWiQYx1 es/languages/coq.min.js
sha384-BA20C0n7Y0nkmgI2mXmwhVoEr1VJgnQgJUuPWAo3wIzHJ284YDjDzQiEH4wyIRj8 es/languages/cos.min.js
sha384-60K3+FM5YGtsBF6SeImyf1oObYrNWVttYlR1CwULXUS6e6VgNw+Ii52Y+edlKNW3 es/languages/cpp.min.js
sha384-jOortbZwoTZREM3Yz79S0e0d7C1DVKrf9anyMZRLwDoGNUNvqSdm6Q6Dxz7VAvo+ es/languages/crmsh.min.js
sha384-EXLQ6RGvwcpUgHwicWj+9YptgIYX0JjGlujLVusFLqU/Q1pyJos/GL2C+s9Y0P6c es/languages/crystal.min.js
sha384-hl3i4FvB/g2MF5+t+JNINXKdpKqxRyjh6f9S0IiYrKhVzSa/gvU5QYkvmrkiGAco es/languages/csharp.min.js
sha384-p3EYWPA6ZVKj+6sn22bu2k9u4qWgTT08yzDKLf/JiQYLSHPQAd1GOApSwPfL+dtw es/languages/d.min.js
sha384-XVdNt2CpJB8itl1s33KXXawHmM1LXmEIQHRhb0etjkRMc2oWlaNkuOkbnK1drBIC es/languages/dart.min.js
sha384-AZLFy2/2tVtPUL2bwigo8AQUc1yS4ZPtrVmtUZkyvgE2DlBAV2zcZ3e1gp29+vxS es/languages/delphi.min.js
sha384-9iIzygbVk2qNWpr8lfJzr+C41jNUrAnezilmHyWHtVPYrO3ShGQW3b3k/YmuXfD6 es/languages/diff.min.js
sha384-WnsRwhzjJ6pXB+zbaNdu85q2DxqHV4gRwuekrwNEB8mfmdgUO1W6sR84OKblj1Ce es/languages/django.min.js
sha384-8f0yIHM5bxd2e4rR94jphly5H0Ky54QJlWbvEtpOHsP84oMjqG3ryh8UKF/No7hc es/languages/dns.min.js
sha384-j72pcGQEYlNS6h1TsxIPdpc8OW3Iks+JzLl/iUU2QEGclvNhBPuYETsd6W9yDgsm es/languages/dockerfile.min.js
sha384-y7QtbW8lD3OghNZgJPdntQaurkwGYddyZXrzRqLSpiKldRuuGBaiiuz2zrFk+4se es/languages/dts.min.js
sha384-xRACefz1K9dtOpvZdMJPshyWd8hcOQYFmutbv7AyLFl3Sr7W8xoTX3wz6VatHMQ5 es/languages/ebnf.min.js
sha384-TvJXN2h1/nA7RGJGN0gdgt1tkPLjLIHBk5IQ4ivbwMwztOL5li+Pb3x4jQTNn89T es/languages/dos.min.js
sha384-c5adijIgfGz0btFVrZSjMhXlwI29VI/9Wr9z1mklRwN7Vp2pWxlLh9jpWnj1xEPB es/languages/dust.min.js
sha384-kjJMvH5Dsm2vhm6VRPe6gb5IbgEaHuYyeX4aeWJTNr73ehupV3gDZFG/Ox+Oq1zO es/languages/elm.min.js
sha384-7Tqmjp8jUpQRhgeZn9STM2H+H2olbPXLbcY7tMy+nY/0d2TqMtrZ5L8DJTlttqBM es/languages/erb.min.js
sha384-s9yBi8t2DbwEi+giYDBGdZaV49waAvnQzOAE8tYfq1jstmiGEWIz7icqq+OrVC0q es/languages/erlang-repl.min.js
sha384-kEV9Ot3GbqowIdKE6uv4tVFkamHEKYycDBGO4kc2MYZpEhn0BCM23F/UZ/v7pXIy es/languages/erlang.min.js
sha384-3UUh+sF4Y48uE/zrby44NgV1khlYHd6vcIa3tGRTiV9mKANeUxWhSpGeeVyQgMA7 es/languages/excel.min.js
sha384-5iBBwcTdQUli5yXrOzI5rDQkwnwaMZpIb/by9GPkCMuZv3xzWbK7AWpKloFDZXf6 es/languages/flix.min.js
sha384-xRM/OGttkTgwNzRA2A4bzrm/uO1XdfevD+nsrm1JmnNi1L3vnHzu0ruFoHIiXklY es/languages/fix.min.js
sha384-SLaeelW7MfPi3Xtj7O5+ikZE1RLV/1rq5v9Ct3XOYRXH0lT8TchDBbfYYxXRslSN es/languages/fortran.min.js
sha384-YdGQE8QLTN4h0m98T+Tht6dfBha7TJ11tucm0vJV9tcFip3BA3akh6P6QYX6HevM es/languages/gams.min.js
sha384-QoGuN97OXVUDpsF9U69Kp9bvpFnGgC9qux+wp3/nA53iAH5HW5c73jxYljKOmbwV es/languages/gcode.min.js
sha384-sgfLN2q/f8MRZPYd4x9zVXCVt1DW9fkLU2YOvXd9nnSMGy5u+S5W7lflXewUuKlx es/languages/gherkin.min.js
sha384-XT53PW1GWBg68S3ivf1MXYHJf+dqDMp7Gz7XsBsL5ET0A74f8285dnUnOTpGc5ve es/languages/glsl.min.js
sha384-VhxOUjCyx0YM3VJZ2OEYzIOB1pLOcSYXe7hGg06B2isg7A7Fm7RgxHelu5OJvvVM es/languages/go.min.js
sha384-LExTp8bHfN5/w+1tyr3Sc14Sab05sIG7BpBt2jy0m4pRAr2V0gKuANs6U4/9YrjL es/languages/gradle.min.js
sha384-4sBJlYiMBBx10XUHo4d5VqXRZTe2CC9QqruZNgVNVw6akuTSaCSFVMFKHyDFGY7e es/languages/graphql.min.js
sha384-UzI2QiQtjkv2jHt5xLZSFB57+qyY9muGKFiP6m84uCpaEHthj4//SHpfTXVUf7oR es/languages/groovy.min.js
sha384-L2WTQdVgsDx1h9oNgRmKsIZVw8YzzGUdsMLPSyIJzZlDop+1MLMsuOQ8c36kQJPd es/languages/haml.min.js
sha384-oZNKmpRNXQHXY+UynPeuF/1aK35s4W6Ja6Bu4QWmPQumruNbz6whGAoGZ8QGXcg6 es/languages/handlebars.min.js
sha384-u8f0KdHcGD55uVnQxsK8WDhPgcBQJ2zwORMVexhJHEWxzfYyNMTtZHp/HOAaUAfz es/languages/haskell.min.js
sha384-XjEZnNU/TiJI2XqhEVHArPttkfOeIOD4fY7oJ2rm1Ve5rte+yfEs0zypImY8g0MK es/languages/haxe.min.js
sha384-NBVMGiglIlB2W4bxddRI3QuNl3IiCFSWBmjjibIaoaUKlxYqGpVgXJAl1Pnroekc es/languages/hsp.min.js
sha384-WusS+7UEcOBN0SfEooa/rXUoV6vNNfu1TpVA+ozkmshpAQmcnNDdhOrK7fIw9xVL es/languages/http.min.js
sha384-yHDq7ZVnCv2VCBulaeRw6+zIF5YHQ+Paq7Y69z+mHpI5rltDhO+uaw1QjmDYznxC es/languages/inform7.min.js
sha384-tSp3ufyDATkuJl0T8eSREuyfjEbSvhoWhlojNSs8zh021xpHk1cnC3jSelUDCr8m es/languages/hy.min.js
sha384-aC26AtcHMLfACMxvaY1KbB8a57tHVtA7cCevB/+OgM7JIy0DiobffHXZcdJVJXtl es/languages/ini.min.js
sha384-h8vOGWupGKWztKwsBmDF2NRny4q8UtYkkV/f4OHU+mCU0t9FcVjOBthcOGrzpPjl es/languages/irpf90.min.js
sha384-K14xb609UVbQApsKchLE2KR/DP2vM1HAF7fvrAy1S7FM4NOhRFpHXn27BCWcPCkt es/languages/jboss-cli.min.js
sha384-kAPy7RwL6jNI6p6tuvat3rMzmR9rXOkumjP+kpA0r6/Js/dWqP9EKcq6CeE3nRuJ es/languages/json.min.js
sha384-KHaMF7viMgBxcOIY42oqf123L7AToPphsPHe9pNHAFT2cus+FkXjgpX+I2sHFdfh es/languages/julia-repl.min.js
sha384-c5bwNMcuEuaiDNjIBwDgQvrgm/2n5d8JgCBCaxxGHb4BKHeFmgT2rpcxBixOxYqT es/languages/julia.min.js
sha384-ZhQB5pXRdLEzbkYoGqjAUDtNSiPIEZmlZRppecYaoemBXBRqzjGOuZgT+Y+hjjUw es/languages/lasso.min.js
sha384-PNWrEpOeP8pe+5JDrdJ8AhP3V6v7t0k9o4hTYpsiJ6CCGE2v2rSUu7GHEG+2/9F6 es/languages/latex.min.js
sha384-mcMGg4PfYi36dQ0vKGSMkTsH9yJfzXAqMK32lxsOYVnJ0y7eMIFzagzXlqvNZog8 es/languages/ldif.min.js
sha384-dOzq1SRILYYDZKSeK+vXoEug+Hf3bpAEl/EUGV0ym+qwxbOSpgrPPrHqif6QoXgW es/languages/leaf.min.js
sha384-UvvtjKfveYj114eR7xShZW0uZcJpvdmRQi9EM2b+drvd62KGUz0/Q931G7fgfKpE es/languages/lisp.min.js
sha384-WTVpBn9XSFYtDhoO6Mw7vFM8wDHw1H7K9wPmmRO9VqKBWQBC1f8iJ1n0ahWCpPVz es/languages/livecodeserver.min.js
sha384-GShVny3xv3dpqDLMKYECc8TzOCpHxSVuDqEzzO1cOlndx9Nu59PGaXehMNdjNqpp es/languages/llvm.min.js
sha384-39PgtcZ330tgowXUcDzkyBDvS23hr2EVUUytBtm/mzks5gLNJcCTqdtBKTCs7CdC es/languages/applescript.min.js
sha384-ldmsekWb10qzqFrv0bHZ9+5l2gDSUh6dL9fJhc8RwnKeSMI2lFGCDyIOtPrAxcWJ es/languages/lua.min.js
sha384-D7mkPvnsaI0TvOw6XRSP4ZrOucZOD2irK9OMYe8L2A2prjXVMqvdrpc0dcuDpwH6 es/languages/makefile.min.js
sha384-d80cU6Gnl9zXFOxN0WIl387pH59v+aCr6W2BYTvv21/khkeimy/F6wcgn43xW34+ es/languages/matlab.min.js
sha384-t3d5q7EnjFQIR7QP0SiyGoi/DKl1NoykqVCrITQ0shIhtQWoyGHoMM5rPya/bGxC es/languages/markdown.min.js
sha384-hq8So73d+B6X+RVXosjZMuB8haTEeR4nxdU31PBryCNe8Qy8BDZEXODO4pg3P+Or es/languages/mercury.min.js
sha384-SUTHc+rS43mZzOI4a29Xg80N9joja1ycmARDXCdgrODOjOovb8SGk8PJ7/2LniNQ es/languages/mipsasm.min.js
sha384-rVsyssFcio7efNEbE6gVbdnB3BEEBU92DYjtNhwQDxYjfpkqE196x9F/x04nXVKt es/languages/mojolicious.min.js
sha384-plHYJ8VJKixCjo/EmgJE20kfX0r/aZFgWddgdAKz6hXcLQF4f1pmwlT5a6KP0dKC es/languages/monkey.min.js
sha384-9MsQQtEiywaN44ZVi70PrWxmwJja7AZNxxwgbx55mKOinJUMm/GOA5EtZzAAGJHE es/languages/mizar.min.js
sha384-qSVG57Ss1jxfVSC8j0/1X+nEwaI8FI3u6qhBtHNG1z4BWvNOc46/tFSSWn4oFy0O es/languages/moonscript.min.js
sha384-WsLwTkBcY6szkz0C7XLDvTzSo3+JGfzoRf0lCnw/sRfSLa/4u1ikYbDeaFMXH44W es/languages/n1ql.min.js
sha384-5JY8C431kLMMiy5TUC/yx9QXiqISNfjyU9g8iFpcjldO+4oTVNENSMUyzWouUIZx es/languages/dsconfig.min.js
sha384-tTOtfxuwmyoqerS8hoUg6zi1jXqh52AVnyPSZEivcPAmHoUcJe+jKLMyC7YJKFEs es/languages/nestedtext.min.js
sha384-8QJemJEVcke7RJbtoENAvHPeyoOf9YB1j/1kO+TyL7yJVrLmxgcOuyp9pNlsIp1y es/languages/nginx.min.js
sha384-w9IdZsE8LUBia1BtNi5pcobI6EvFFNJ4QorCo71KJ+IGg4e9FQMlEkoXqeX+dIiM es/languages/nix.min.js
sha384-OPw+vNBCeUcX6eirA0y9OLnCK/y7ikVWujY3IlFpCk6jaTzGL7Ybe8f99L9UvnZc es/languages/csp.min.js
sha384-4HNPlmEh6qDsM2gySjoAiu8SEaHkkm69i+EZV8ZnzR5hYqyXJXNGCYXH7MTCCzHs es/languages/node-repl.min.js
sha384-lbSCr7PJx6tjbFNTizwuPBZ54IwvB6/uZ4Sm5E8WSIwNNbCJga77Bv9SEp6k74bH es/languages/openscad.min.js
sha384-sDdlAwRWKDeqEGxPj4CQMH22Nq5TfOjqJpvP1ANObSh46CKkCAUq+a4UuwkyCB/j es/languages/oxygene.min.js
sha384-/U4spkrGxa5+Sv9mDIgSmLlGa35SOix8iS1zawnuNSqdFmtItUOZCj3L3odVsL6f es/languages/objectivec.min.js
sha384-YZqnKrQjIGSSH3VVOqjjIKTWRonN8roDHkl9Et/N89uspB/Uz1e/SsPvcpcNsZWb es/languages/ocaml.min.js
sha384-/NYynOuLCFOSqAql2N3HI0V/6c15HT/PFoJXTj0Me942DscAAAnwYtvKPDH1Vt+7 es/languages/parser3.min.js
sha384-dNw+j+bMaFJ32Bd5FZuz58XT69g7pOykA/PPBTkAS6lp6KaVYhfvhVfxbrzBT6z+ es/languages/perl.min.js
sha384-MWyax//BxmG8CLv2T8zTR8s4BN4bJegmowaaJqwCmSiBUbHkWss76x50iar2KyFR es/languages/pf.min.js
sha384-KgeHSN+DgL+0qzCJu/OkV07pAl/NEyyvnjGNy3dIUJ6o2r6beitH4DDGWd1ID1/d es/languages/php-template.min.js
sha384-Auh6O/uM8vY7GTFnoMGpqRPnKAG5YviQRofpjogvDLwB9UbRpP4fyVFWH8exq+vm es/languages/php.min.js
sha384-YKAZgvtm8LCn4OEjZTA96C27pOpXEZwW9FPfpSL7PyPB4rsOv/JpMHrbjAcCki3e es/languages/pony.min.js
sha384-SUTbaRU+H7m7Qcb5Psan3sSpWFws+cDcwcfUgOsUqXVDt3MhReCJp/aFuyDe4ZjI es/languages/plaintext.min.js
sha384-kJChzNG2klFzE1k0H2J9Fv8dVkGvMG2/VEzBRSQr1PY9SzfVMTvGjEBMa0udx6qs es/languages/powershell.min.js
sha384-UHgB6jTvcqc2cQ6iGcM/z1Yaq7uRirAJXcbpRkfo1fOIEYdpoPRdT59CNgY8JjM8 es/languages/processing.min.js
sha384-Qs4WT1OjUtIBeacXcQtexpd0dmzsFUTTuDIx61ffKrcSrM+huIMb3f4qLoc7ZfbM es/languages/profile.min.js
sha384-tXyvqGS76aX1yjTMJ/fJAhhqqmOvyuDvMlN6YfK+ngS6YrTCF8bWR/v1o7BZao4y es/languages/prolog.min.js
sha384-R25GsC02zdv3MYJk+ptf7YKCQiUGiGkDXxvvHrw9cXfJFZCZ5Ki6y1gVVABJ6HEx es/languages/properties.min.js
sha384-khMGUzdCGj4aYgXPQjNenoLVXbchLkPAD3RQBXK4EIeM8Dkr/gYLlOmKJ6gPzpVX es/languages/protobuf.min.js
sha384-4ce0XOycxBqzIX0vlznCMsPxT1h96plzffSlqnQYIRRqfVVU4LY2CK9aihBDAzTr es/languages/purebasic.min.js
sha384-uxWjnGlv+PAoMgeTBwCJNsayFEM47GZQwIBa7Q+lwvUxVf9InmCl0IsoJIWbqtDV es/languages/python-repl.min.js
sha384-R9vTEjiXUjOdkFjmPx+cgsENrdAgQx94VQrwYT6696ITVXcFDNxgK2824saDRQMw es/languages/puppet.min.js
sha384-P7ZpJgZvqKgrE3fk4gd/UkrED2v77fKVy+lc01WhzehTWip1LCZFnoceJnav1R10 es/languages/python.min.js
sha384-esAU6ykOfplCUC+xmxGnYJzMSM8AjWmq0LIQT6N15YJEACy5lvwgAFT5VpV2YqP+ es/languages/qml.min.js
sha384-m0OI/F2W+Yg0rOimJbeWCBP6wRsPTL/CUzJlIqu2ZruCZ7wPdxWrxN5o4NUoRKaV es/languages/q.min.js
sha384-XtTXt70kiNJ51p4W3TdARM67JJ3KJnrxCDerOhRkMFeGQuoWw6GPdzLFklUJNP8z es/languages/r.min.js
sha384-En0QcUPR3CN/YdCJk5p45lsQ+IdfIDD9Bmf1muNGshwDQ4gxytetx+Ay++yKfD5W es/languages/rib.min.js
sha384-oiDiQPfgwpQ4DFrgmDvEJsLSZWO6097V/+OWXNK5sjvEYTTYbxuiVFnTrGj4+egx es/languages/reasonml.min.js
sha384-4uml+GCTSfEVBUvcRBjv0qOQ+0gMJYePHZt64Pks5m3ZTWo3nBEGEV1JngiIDpCf es/languages/roboconf.min.js
sha384-QjdjYGk2YZ3HWLxnwZJRf0xFOIl8HM87phcarngYgQM8hE4FLy+VgYh8McaN25yu es/languages/routeros.min.js
sha384-27yXyYaeKWakQkvzW6oAXm/n1E9wog8d3jgKTS2ualuuREHRpf/YlLa3WKbLqmu4 es/languages/rsl.min.js
sha384-RfkLr8DOFitylLYPSmhmzwdPyLR5VWsDkxEOuVUatJsmu473uxa3FSQ3C/G+AAJD es/languages/ruby.min.js
sha384-yLOWDyP+Z0B7ZALmuBizuJBZfmUOVgVwFn3SvKLpMyhIwDBkBC0mSAsWbv1yuUYL es/languages/ruleslanguage.min.js
sha384-PMaviVaDEMOLFz5QQcCzvzfjfqv/PB3rht+/AaupaINLCVzNciChk1BMPdxim4Hb es/languages/rust.min.js
sha384-DZfCoAYwSmSQbBd4Dy43Imp8lJFjkLK0J/ghZUf1Qkxjuot9k4+wGwFbfLT9DvOZ es/languages/sas.min.js
sha384-XMuCTxdwWNPxFmoQqnmhFSTqMoLWVTSeHQOKKl7D8XdjJMn3afua7IaKsRc+TBUQ es/languages/scheme.min.js
sha384-ALtgI9qdx2/2PmtlARmjTINImPbEA0bFcncZTb7DTrG+6Gi5jbIR25aVMrUgWYpM es/languages/scala.min.js
sha384-CtKdb4pypxokzOJ3C5TTNIKkP7W6DFzBSBnAaPqEstT1TtVdNq7wUZEi56uZHxUo es/languages/scilab.min.js
sha384-UWc6orjSjXaXCcitp2u+sa0zjKEXX7PCc2YUH9SefuAlSt44s+lPPZ7FRpACK6xN es/languages/shell.min.js
sha384-kWFzaZouiPTuSjQH/lfuWVQcM7OJohaGHGcbqtsjDvkpYGjzzxdp5R2E1AGTW/fs es/languages/smali.min.js
sha384-7X5OBJU3akhhJrclBrKFNI4X1BOedhKAri6OGN/2kGBscIlh3a3t0HSp+L7Kw91e es/languages/smalltalk.min.js
sha384-wdyHffROqM2P6Wcll/3ibx/DMlZQHf7T/sYvvwMjhq2vsDjgjDcW9yfEDZCNkE8u languages/sqf.min.js
sha384-sN6Tj2cn2cRnnkuaqD2tnxe1umGIQUvcUcYIp5DoMI2WZjRQZbWE1fI+JqHYV/r/ es/languages/sml.min.js
sha384-3tJOaaBAtxzTFLi8laClreE0HSIGsqec2f9IvBtgF3zEUI6pN1HbiVQJuLKjdBJe es/languages/stan.min.js
sha384-LXDrWg8ppxAeIW73QXExaTot1vuSYxICdEbW376anA262/v3oQOLwOLtZ6imj3Kt es/languages/sql.min.js
sha384-QsOkY1Uhncwq26umIGn6Vca3jTrywrSeRldSHnPOMf9tcLPTkwo85iEzDiBThRb3 es/languages/step21.min.js
sha384-JNb864St3EpkgyOiiRlg3wDr4X4WuUYUR9D8+sJBmQnSoPMx8HI8k4iMPrmyBMZD es/languages/subunit.min.js
sha384-1wDqXeFZh8O1cjrXSSx+pSWo89dc58LCxQTd9pqBGfCdRs50dQmfOuUXHHB4ITJT es/languages/taggerscript.min.js
sha384-knrHLDK3Tm8HXOsMBWDb/OiAl99SMdAm4Ok4stGPHTuZeP5CPunL8Dr4YJcAoSLr es/languages/tap.min.js
sha384-/U1N0X3Ll1NBjbfAi/gYqq4iI78qvIivvbxOuuymfTnE58yXB5u9mRFSsHwNGkZU es/languages/tcl.min.js
sha384-xlzdxXLrk2qTpARdAP+uR/+R0Ht590qzEllXouAyHoUf0CxTFB16u9hbT2dfL8nI es/languages/thrift.min.js
sha384-gDAP9DQLyouliuLpuagZaTmXFot3RPogaYXYTolIC75craqt2i1yF4I0By4zfYoZ es/languages/tp.min.js
sha384-JeAPVcJq2DYplMwRoAkmFu9kMGxlX1dZYAjRO4gVNVQLPhukn/RWcZltycmaJ8Uf es/languages/nim.min.js
sha384-5Dayld5JVlwawPTQIQV+sb00xBcLnJQCYpOg4T+QMreMcYDa5nuob7LC8tcUE1/o es/languages/twig.min.js
sha384-dBz8lguFGhFBldBljaMwkTYK7T5c8EOHf8O7KbIrNvy1+6nqTypyk7feyXq1HkUJ es/languages/vala.min.js
sha384-l7oc6bdLJuMSNAVcXmTgpNp95byRO2MrLN1x8nQzOE2V2k0bxwaZ3WS7VpqIbEky es/languages/vbnet.min.js
sha384-iCdWQQ7K7atU9gDqPtjBwnDiVDB/5dgE8oFmd2cVuZc/hgOsZcsonMtKiTYrcGZ6 es/languages/vbscript-html.min.js
sha384-IT794y7mK5VkRRPOnKSiwZq+NV/y06sdA+U7Snp/ehVqWlOpEJ1+jU1uhRWylje/ es/languages/vbscript.min.js
sha384-j3XuyvxJf1mF6U7YTexmONaFJIwABSrCdWYlKu+/z2InmzQPTvmsRtPYiCF/SeP7 es/languages/verilog.min.js
sha384-qID0e8b6QD08+lEn4qu5LXFX41xUIX3ijn/ZO/2JXpUaxOFoTaI4S67JQ3ZKjgYb es/languages/vhdl.min.js
sha384-LAo1L+bHtI+1gyo/E7/kPcUIzDZyDCTNMwOozCbCRuStJPI/BGdEQoOs7HiEJ2uQ es/languages/wasm.min.js
sha384-fMmMGmxKMX9Ah86SInRfldQzp+DMBk6n1xFQHq5VxeFr3ckOkDDhARk9MV1C8RB3 es/languages/wren.min.js
sha384-yZayuFLAGRmYcGfdWrUhIo1SAXa97iLVhwEk/Uo9Q2AOUAojlal+LHefF3XeeKZA es/languages/vim.min.js
sha384-r6uPWdIq6qL5vcrem2vpYyjZtWHZTEWd34BqeQp+BikFkartSiwiA4u8Wm/bzgFq es/languages/xl.min.js
sha384-TZyTKXCSkRoZ0EGkhheBobcawGJW4NBDoBXIIG+eb7j1O3O74KNd7tNpW8xv46pd es/languages/xml.min.js
sha384-yZx4EKMqgf1Iuhw2wtQTj/anxALhU0RgqUCp3obAMxtuWJsjVKuPIP0sxICDahAN es/languages/yaml.min.js
sha384-RFkfOB8b51LWTL2UoDf+TatiHCx89/HKtDioYIJO52gm+3AFBMDZzxiqunoXENqD es/languages/xquery.min.js
sha384-OclXcfwpSMhVjyZX+r5Pwcw4bJan/8qqtf9y/XerFAMohCL4cIVmV5maFMB6mZR7 es/languages/elixir.min.js
sha384-miFunA1MJwniDxuSHUNAPOdrtrNXxRIPUIAK8cxE9H3Yl0qw8W4bmRBhnVIw3xVf es/languages/zephir.min.js
sha384-0Iz+CtVEY6qU/0lKS7/lfYB18CVQ3llKef6zFZorcAyVGKcDdPlIOIsapZIbugUW es/languages/lsl.min.js
sha384-pwEVbsS/dlwgm6iJIlf9ciqj3eFMGyiAJRMiPAho1uCyT4xcsRaexIapIfyMN5jm es/languages/golo.min.js
sha384-hXpuages0l3ypNsDu/dSQK63nqBADoP+CRYmjZS4l72aJLzuF0O0SlmKn9ZQYjW4 es/languages/gauss.min.js
sha384-rnLXkiQ+LLtwbe79/FOuAE6jMTEyFFZjXgqLkwWf3ojDN6zz5DxalnDvWzx9x1gg languages/gml.min.js
sha384-1tFwsz/aByTbp4xkbzZ3wNSZGcP6LVC/BkL7AbPVM7wr1yYntBLUz7g344IZwNpS es/languages/mel.min.js
sha384-cr0jVt+VSx6FuCsrWRI827BVqXAj/YyOoXM6EdUx7FGP5v2Oh3YIkqRiIhpdDEn4 es/languages/pgsql.min.js
sha384-fa5mRqCXBdbHyNd2usqJErFjdHdUy7yhDMomUiUfRn6Yyps5L1hy/FHsCGRVAL+s es/languages/stata.min.js
sha384-caKYdomSSvvOmIpFEoj4HNg90kItT+/QTvCEIuhsc6eG+r4wic1KZ5iAQOy2TyXl es/languages/x86asm.min.js
sha384-Ce4s0i9ySNk3NOoOVnfRP1qrVWXY/jctY+t1gsa32GSunq9YpYiDSslivQtyUfQX languages/isbl.min.js
sha384-6PcnJol55BFlPHDdjciA4Q1bw+6cTDFbqVOyDZVJJzU6EnLTUY4R3i9SGgpauCEK es/languages/maxima.min.js
sha384-JJBx/XMYwfaXZDPsM8jN1knmU90C1OgxJSX7smzZtlHUbJsaqALeYL/QNWGrQI7V es/languages/sqf.min.js
sha384-AutJOyGwUBE+NByi2nl3jpm0sbIPu/Q5ILDSTvES+UIRBbYZtc8cdbAKrIW8pOc1 es/languages/gml.min.js
sha384-dBbglMSshAkm0PFXOnutg5oDZvbiDj7MvK5OdADaYKjPWjXM6uWIiAJSWGAJeB6L es/languages/isbl.min.js
sha384-lj8q36L9LrWtCjmyJ7ZaN47h1G/bc69JJ/4TjCIUKcHVY4/cefc/AugIzDa4gVBo es/languages/1c.min.js
sha384-VFTjWkEc8VJaEPRC1HEJIf2MxWY6MYway7uPea674H4XeuU21tlj3lKYxS9HaX+b languages/arduino.min.js
sha384-zKrOS8dVl14NzZNuqgV7AEVg5U+sWniodcjUlWM9CCciz+0TFPDXcFY6QbqfIUot languages/nsis.min.js
sha384-qEPMPo7LSylwJca8bTw6fejLLRggpTl5O73ctAJye4ce0jDLVGIpYJxWbgYUNSw8 languages/fsharp.min.js
sha384-u6tiY5ae5rEpPiLWlGhnZ3ZlJ341GiMAJskvxthzwfnEBOsXxHfpcg4U3ezGOuam languages/javascript.min.js
sha384-69SUsAH04ybvCL5zTSP/Q8RYY1/eviJP6QhrmBYdeqnB7GYVefRkQ1Fp/GN34Hht languages/livescript.min.js
sha384-DpPGF+6sbTMvXhKDpPBQcUjJDPxkSmrPOaHY4Oa5cjWBhVcbxzqBWFBSOy4jiPtp languages/coffeescript.min.js
sha384-6AhUr5ai5ut61xhm6XI4mmpjAVQDyVqnusLBRiOyrj7ns18vbWFBDge7ZLHCZVeQ languages/less.min.js
sha384-VkkVVRN8ntJf7WfgK4ln76hm3gq1MjME+7MIe/FE26yOcuUXsmzgLQ0ebDcO6j0g languages/css.min.js
sha384-kcgMlTi5NsOSYb4T9Lkd8zPdA0eAjb0EulYq9bx3yUZAYkJRXtnxV7aqJCQucwb5 languages/scss.min.js
sha384-eRkG6TM7W+J1E6Vhv/BMGJsSGvv0oqWxgCLG3eSFE5v+9Dd00Djxzfn0COyUmflz languages/stylus.min.js
sha384-IxN5FSe738BRLIrJ61Bb44l2KSqxsLo7sX69XdEbrrGf7UZUtZ8cgr74MwJnkIPa languages/kotlin.min.js
sha384-rx87NCGurzhoKlFCKYuS/V6m0atsxuKkt+zB8Wcv6B+Er7MITA0wtYmuCNc4ETYg languages/java.min.js
sha384-Xz9GP/hD/AJQIoPW+xRJsWSBmqfoiw2+OAkAzXXlq3xEPn5JEK15wqwsbeYXRlAL es/languages/arduino.min.js
sha384-jRDeEN94ToDA5MplOidcqNxbXU+soYswW+UE559+DKw5ttIdxxyuqZKYOch3JaXq es/languages/nsis.min.js
sha384-EgyW+jqZKP9Pzw7iKQBKGaxmHeDzRheRDc0n1zX84qSaMG1oQLoaaxa7yw9ZV/aj es/languages/fsharp.min.js
sha384-Ygca+ejUkK2wAzzEKqJdaZ/e0h/ZWVGRpTxhhtmR0gjeN/opX2ys6Xq6orGbtGR0 es/languages/javascript.min.js
sha384-yIlx4hc9Abcl7HWMwmInpW2CgPybUGKe92/m/h+7RHxFdVx483cVl6Tcxl1kY75d es/languages/livescript.min.js
sha384-1JKtWxJ++SpfFe5KNsxCVhC3o5+s1SUiyucM7S3IgrY1+wCE+FXkHwoFsMKFjLHm es/languages/coffeescript.min.js
sha384-uzS2/t7ca1qntAYWC0rToIud2XT8OUWrLj5syYsYdFDRkFFLN4Zxr3GisbAVpnf+ es/languages/less.min.js
sha384-0PrHBG4Nj7gqPWHPZpgs7xsBX8dYl4/a9TJxkTMUKWwKZN1ZFQ5Tm2it+PuFhqYR es/languages/css.min.js
sha384-2zpoxZFQ3MF40he6DpFFu+473/MZDmeHqzu3FMCwRwgFF0TAnexWphtN3W1DPP++ es/languages/scss.min.js
sha384-qiQygFwki0pIV7aHrbPw0BF/TG7J8R9w0P/qG+TwqENQobcP4OTkhNyK6KQvaDGQ es/languages/stylus.min.js
sha384-r6cZvvk7rJrwc2xN/mhOjIqxeqqXej5COQl9H06oeVM/SMQndq2mFPcFEWldv+uP es/languages/kotlin.min.js
sha384-LdTGxktmW+I29afWlfxLaCeOs7o6wBzHd3shePR/sEEZYcvvLzc1y9PXl2kQc4aE es/languages/java.min.js
sha384-U6EP4euCSSCGBW/OqTosbFw5Z2/KHrdLSaKnj9OJ46N3VcMRLCYWdj4Ix5t/Cs79 languages/mathematica.min.js
sha384-jhPIl3eNtxsjVlcYVqh2eTi4exuAwfU0+HVqjR/aMUlAKzZSDzeAdlM2jvFsy4F5 es/languages/mathematica.min.js
sha384-0W5LulXTz3es7ITbVzSnmKkUtfsCJLZapHro1oFmIOjmTaVe2fzGZfNcTg75Z377 languages/swift.min.js
sha384-qoxWkKeiWsrBcgxgTq2dPVj2lI1FSbACfbbjSg1yI3a0a6c4z5OMqegOyFb5sG3s languages/typescript.min.js
sha384-KpfoNrrbBlkHmXEKx/ZBwtkLHAPWRJE6NUrwte4bR/alPJr6bubVDcbBmMGDQAv7 es/languages/swift.min.js
sha384-DFrS1IsS0VfzKDvpxnuLwlTGdz67SrbYIa/Oe9bhZOd7xLhAsdLNd0gh4ap1ZMRv es/languages/typescript.min.js
```