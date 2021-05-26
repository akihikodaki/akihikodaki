# Akihiko Odaki (小田喜 陽彦)

## Old identities

- akihiko.odaki.4i@stu.hosei.ac.jp (when I was a student of Hosei University)
- nekomanma@pixiv.com (the first email address I got at pixiv Inc.)
- nekomanma@pixiv.co.jp (the second email address I got at pixiv Inc.)

## Telling Something to Me

If you thank me or something, just give a star on GitHub.
If you have a question on this document, comment on GitHub.

If you want to tell me anything else or if you don't want to use GitHub:
- email to akihiko.odaki@gmail.com,
- mention [fn_aki@pawoo.net](https://pawoo.net/fn_aki) on Mastodon,
- send a message to [@aodaki:matrix.org](https://matrix.to/#/@aodaki:matrix.org) via Matrix,
- send a message to akihiko.odaki@gmail.com on Google Hangouts, or
- aodaki#7967 on Discord.

I have a Twitter account, but I may not be that active. https://twitter.com/aodaki

I'm kind of talkative so feel free.

## Characteristics

I'm a human so I have human characteristics (e.g. I operate best in 20-30 celsius degree). Other charactersitics are:

- I have never left Japan and am optimized for its environment. I'm a native Japanese speaker.
- I have English language ability sufficient to write this.
- I prefer FLOSS.
- I'm kind of a low-level programmer and familiar with C language. I ocasionally wrote MIPS, ARM, and C++. I read x86-64 for debugging but my understanding is kind of fragile.
- I have some knowledge of UI programming paradigms since I learned them to build [Mux](https://github.com/pixiv/Mux), a UI programming thing for Unity, and coded some Web applications.
- I use GNU/Linux with GNOME.
- I prefer to work in a team because humans are interesting by nature and a team also helps me determine my role. However, it is also fine for me to work alone.
- I do any kind of programming if I'm sufficiently motivated.
- I'm from Ibaraki.
- I love chocolate.

## Timeline

### Before July, 2017

I was a occasional FLOSS contributer.

- GNU binutils' ARM linker bug https://sourceware.org/git/?p=binutils-gdb.git;a=commit;h=5025eb7c0d87b01507116353b5d63b163d7add3d
- elfutils improvements https://sourceware.org/git/?p=elfutils.git&a=search&h=35e49cac53a97ae6c51190c8e2d35a215e188bba&st=author&s=Akihiko+Odaki
- ARM and EGL support for QtWebEngine https://code.qt.io/cgit/qt/qtwebengine.git/log/?qt=author&q=Akihiko+Odaki
- buildroot https://git.buildroot.net/buildroot/log/?qt=grep&q=Akihiko+Odaki
- Ruby bug https://bugs.ruby-lang.org/issues/13648
- Xamarin.Forms bug https://github.com/xamarin/Xamarin.Forms/pull/303

### pixiv Inc.

#### July, 2017 - June, 2018

I was employed as a part-time worker for developing [Pawoo](https://pawoo.net/), a variant of [Mastodon](https://joinmastodon.org/), a federated microblogging software.

Mastodon is Web application and built with [Ruby on Rails](https://rubyonrails.org/). It has RESTful APIs and [ActivityPub](https://www.w3.org/TR/activitypub/), a federation protocol. The UI is built with [React](https://reactjs.org/) and its state is managed with [Redux](https://redux.js.org/). It stores data to [PostgreSQL](https://www.postgresql.org/) and [Redis](https://redis.io/). I developed for all of its subsystems.

Speaking of Pawoo-specific feature development, I assisted the full-time workers of the team and developed a feature relatively independent of the other aspects of the software.

- Contributed to [Mastodon](https://github.com/tootsuite/mastodon/pulls?q=author%3Aakihikodaki).
- Developed Pawoo Music, a discontinued variant of Mastodon. I was responsible for a feature to generate a music video suitable for video-sharing websites like YouTube and Twitter. The feature had the interactive preview and the actual video was generated on the server. I developed [the application](https://github.com/pixiv/musicvideo-generator) and determined the server configurations for accelerated graphics.
- Suggested and conducted an experiment to integrate Mastodon and [Matrix](https://matrix.org), although it was suspended before yielding any results and canceled later.

#### July, 2018 - March, 2019

I was relocated for developing [VRoid Studio](https://vroid.com/studio), a software to build humanoid 3D models without special expertise. My involvement began just before its first release. My focus was to improve the productivity of the team because the relocation was regarded as "temporal" in the first place.

- Constructed and maintained a CI infrastructure with [Unity](https://unity.com), Linux, and [GitLab CI](https://docs.gitlab.com/ee/ci/). GitLab CI was managed by a colleague so I wrote application-specific code and communicated with him for the integration.
- Designed and implemented [Mux](https://github.com/pixiv/Mux), a tool to build the UI with [XAML (eXtensible Application Markup Language)](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/xaml/xaml-basics/) and [data binding](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/data-binding/), and reimplemented the UI of VRoid Studio with Mux.
- Fixed many bugs of Xamarin.Forms' XAML processor used in Mux. https://github.com/xamarin/Xamarin.Forms/pulls?q=author%3Aakihikodaki+

#### May, 2019 - Augest, 2019

I was employed as a full-time worker, and had some training in April. Later, I joined the development of [VRoid Mobile](https://vroid.com/mobile), designed for more casual humanoid model creation and including AR feature. I left the team just after its release.

- Designed the architecture of the application as whole. (It was modeled as MVVM and integrated subsystems designed and implemented independently.)
- Clicked the "New Project" button of Unity and wrote the integration of different subsystems and many of its UI components (of course in Mux).
- Ported the CI infrastructure developed for VRoid Studio.
- Instructed other developers to enforce the application architecture and Mux best practices and to provide some generic programming advices. My intention was to maintain the steady development until the release and after I left.

#### September, 2019 - October, 2019

Technically I had never had the "On-the-Job Training", so I completed it by temporarily working for [ImageFlux](https://www.sakura.ad.jp/services/imageflux/) team.

[WebRTC bindings for .NET, mainly targeting for Unity](https://github.com/pixiv/webrtc) are its results. The library avoids common pitfalls of such bindings like multi-platform support and garbage-collector awareness.

#### November, 2019 - Februrary, 2020

I was relocated for [pixiv Sketch](https://sketch.pixiv.net/) team. pixiv Sketch is a social network where users can casually post drawings (i.e. it is totally fine to post incomplete works). It has drawing tools and a live broadcast feature.

I had no particular job to do, so I just did any technical things the others don't do.

pixiv Sketch had a *backend* server application providing RESTful APIs representing its resources and *frontends* providing the UI. Such a combination is called Backend-for-Frontend, or BFF. The backend was a Ruby on Rails application, and the frontends were Web, Android, and iOS applications.

- Evaluated implementation ideas of the new drawing tool to be implemented in the Android and iOS applications. This also required the understanding of C++ and language bindings.
- Modified the WebRTC library for additional features on iOS like screencasting with audio and an extra audio configuration. https://github.com/pixiv/webrtc
- Implemented realtime markup of user-inputted texts using [contenteditable](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Editable_content) on Web.
- Introduced [Interactive Media Ads SDK for HTML5](https://developers.google.com/interactive-media-ads/docs/sdks/html5/client-side) to the live feature.

#### March, 2020 - Februrary, 2021

The backend and the Web frontend of pixiv Sketch was assigned to me. I focused on reliability.

The backend interacted with [MySQL](https://www.mysql.com/) and Redis. The Web frontend provided the UI with React with its state managed with [Fluxible](https://fluxible.io).

- Greatly reduced the over-provisioned Web frontend servers.
- Introduced [Datadog APM](https://www.datadoghq.com/product/apm/).
- Introduced [Service Workers with Web Cache API](https://developers.google.com/web/fundamentals/primers/service-workers) to reduce the time to interact dramatically for daily use with minimal cost.
- Introduced [Docker](https://www.docker.com) to the development and production environment.
- Debugged Linux kernel to understand kernel panics.
- Debugged Google Chrome to solve process crashes when using the live feature.
- Debugged and patched Mozilla Firefox to fix CSRF. https://bugzilla.mozilla.org/show_bug.cgi?id=1605305
- Debugged WebRTC to understand some details of H.264 encoding negotiation.
- Actually I still wrote some code and gave some advice for the drawing tool, utilizing my low-level knowledge.

#### March, 2021

I become an unemployed FLOSS contributor again.

- QEMU https://gitlab.com/search?utf8=✓&search=Akihiko+Odaki&group_id=3038080&project_id=11167699&scope=commits&search_code=false&snippets=false&repository_ref=master&nav_source=navbar
- virglrenderer https://gitlab.freedesktop.org/virgl/virglrenderer/-/merge_requests?scope=all&utf8=✓&state=all&author_username=akihiko.odaki
- UTM https://github.com/utmapp/UTM/pull/2361
- Mutter https://gitlab.gnome.org/GNOME/mutter/-/merge_requests/1737

Actually I'm working on QEMU on macOS. Especially I'm focusing on Virgil 3D, a bridge to expose host OpenGL to guest, and Apple Silicon/M1.
https://gist.github.com/akihikodaki/87df4149e7ca87f18dc56807ec5a1bc5

## My Name

### Akihiko (陽彦)

Akihiko is my given name. Aki (陽) means "sun". Hiko (彦) means, well, I don't know.

### Odaki 小田喜

Odaki is my family name. The literal meaning probably just doesn't make sense, but:
- O (小) means "small".
- Da (田) means "rice field".
- Ki (喜) means "happy".

So it may mean "I'm happy with a small rice field" or I don't know. Indeed, I prefer to get things done with smaller code base.
