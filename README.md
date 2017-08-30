# rebar_error

Fake project with config which crashes rebar3 on upgrade/tree commands. For testing and reporting purposes only.

Tested on latest rebar3 (3.4.4) with custom built Erlang 17.4.1 via kerl with
```
KERL_CONFIGURE_OPTIONS="--enable-lock-counter -with-ssl=/usr/local/opt/openssl --enable-threads --enable-smp-support --enable-kernel-poll --with-dynamic-trace=dtrace --enable-hipe --enable-dirty-schedulers"
KERL_INSTALL_MANPAGES=yes
KERL_BUILD_BACKEND=git
OTP_GITHUB_URL="https://github.com/erlang/otp"
KERL_ENABLE_PROMPT=yes
KERL_PROMPT_FORMAT="[Erlang:%RELEASE%]"
KERL_DEFAULT_INSTALL_DIR=/Users/yes/.kerl/install
```
