# Akihiko Odaki (小田喜 陽彦)

## My current identities

- akihiko.odaki@gmail.com (personal email address)
- odaki@rsg.ci.i.u-tokyo.ac.jp (email address at Shioya Laboratory)
- [@fn_aki@mstdn.maud.io](https://mstdn.maud.io/@fn_aki) (Mastodon)
- [@aodaki:matrix.org](https://matrix.to/#/@aodaki:matrix.org) (Matrix)
- aodaki#7967 (Discord)
- [@aodaki](https://twitter.com/aodaki) (Twitter)
- [@akihiko.odaki](https://gitlab.com/akihiko.odaki) (GitLab)
- [LinkedIn](https://www.linkedin.com/in/aodaki/)
- [@akihiko.odaki](https://gitlab.freedesktop.org/akihiko.odaki/) (freedesktop.org GitLab)
- [@akihiko.odaki](https://gitlab.gnome.org/akihiko.odaki) (GNOME GitLab)
- [AEDC03C9AF734F2EC26A7BFFA4BAEAA73536753C at hkps://keyserver.ubuntu.com](https://keyserver.ubuntu.com/pks/lookup?search=AEDC03C9AF734F2EC26A7BFFA4BAEAA73536753C&fingerprint=on&op=index) (PGP key for akihiko.odaki@daynix.com)

## Old identities

- akihiko.odaki.4i@stu.hosei.ac.jp (when I was a student at Hosei University)
- nekomanma@pixiv.com (the first email address I got at pixiv Inc.)
- nekomanma@pixiv.co.jp (the second email address I got at pixiv Inc.)
- [fn_aki@pawoo.net](https://pawoo.net/fn_aki) (Mastodon)
- akihiko.odaki@daynix.com, aodaki@redhat.com (email addresses at Daynix)

## Telling Something to Me

If you thank me or something, just please give me a star on GitHub.
If you have a question on this document, comment on GitHub.

If you want to tell me anything else or if you don't want to use GitHub, use one of the current identities shown above.

I'm kind of talkative so feel free.

## Characteristics

I'm a human so I have human characteristics (e.g. I operate best at 20-30 Celsius degrees). Other characteristics are:

- I spent most time in Japan and am optimized for its environment. I'm a native Japanese speaker.
- I have an English language ability sufficient to write this.
- I prefer FLOSS.
- I'm kind of a low-level programmer and familiar with the C language. I occasionally wrote MIPS, ARM, and C++. I read x86-64 for debugging but my understanding is kind of fragile.
- I have some knowledge of UI programming paradigms since I learned them to build [Mux](https://github.com/pixiv/Mux), a UI programming thing for Unity, and coded some Web applications.
- I use GNU/Linux with GNOME.
- I prefer to work in a team because humans are interesting by nature and a team also helps me determine my role. However, it is also fine for me to work alone.
- I do any kind of programming if I'm sufficiently motivated.
- I'm from Ibaraki.
- I love chocolate.

## Timeline

### Before July 2017

I was an occasional FLOSS contributor.

#### Low-level

- Capstone, mainly ARM support bugs https://github.com/aquynh/capstone/pulls?q=is%3Apr+author%3Aakihikodaki+is%3Aclosed
- Radare2 ARM support bugs https://github.com/radareorg/radare2/pulls?q=is%3Apr+author%3Aakihikodaki+is%3Aclosed
- GNU binutils' ARM linker bug https://sourceware.org/git/?p=binutils-gdb.git;a=commit;h=5025eb7c0d87b01507116353b5d63b163d7add3d
- elfutils improvements https://sourceware.org/git/?p=elfutils.git&a=search&h=35e49cac53a97ae6c51190c8e2d35a215e188bba&st=author&s=Akihiko+Odaki
- cv2pdb https://github.com/rainers/cv2pdb/pull/38

#### Embedded Linux

- ARM and EGL support for QtWebEngine https://code.qt.io/cgit/qt/qtwebengine.git/log/?qt=author&q=Akihiko+Odaki
- buildroot https://git.buildroot.net/buildroot/log/?qt=grep&q=Akihiko+Odaki
- Xamarin.Forms bug https://github.com/xamarin/Xamarin.Forms/pull/303
- Xamarin.Android Linux host bugs https://github.com/xamarin/xamarin-android/pulls?q=is%3Apr+author%3Aakihikodaki+is%3Aclosed

#### Web

- Ruby bug https://bugs.ruby-lang.org/issues/13648
- Mattermost https://github.com/mattermost/mattermost-server/pulls?q=is%3Apr+author%3Aakihikodaki+is%3Aclosed
- Paperclip https://github.com/thoughtbot/paperclip/pull/2545
- Sapper https://github.com/sveltejs/sapper/pulls?q=is%3Apr+author%3Aakihikodaki+is%3Aclosed https://github.com/sveltejs/sapper-template/pull/70
- parcel-plugin-svelte https://github.com/DeMoorJasper/parcel-plugin-svelte/pull/11
- react-virtualized https://github.com/bvaughn/react-virtualized/pull/663
- YARD https://github.com/lsegal/yard/pull/1099
- extract-text-webpack-plugin https://github.com/webpack-contrib/extract-text-webpack-plugin/pull/601

### pixiv Inc.

#### July 2017 - June 2018

I was employed as a part-time worker for developing [Pawoo](https://pawoo.net/), a variant of [Mastodon](https://joinmastodon.org/), a federated microblogging software.

Mastodon is a Web application built with [Ruby on Rails](https://rubyonrails.org/). It has RESTful APIs and [ActivityPub](https://www.w3.org/TR/activitypub/), a federation protocol. The UI is built with [React](https://reactjs.org/) and its state is managed with [Redux](https://redux.js.org/). It stores data in [PostgreSQL](https://www.postgresql.org/) and [Redis](https://redis.io/). My interest included all of its subsystems.

Speaking of Pawoo-specific feature development, I assisted the full-time workers of the team and developed a feature relatively independent of the other aspects of the software.

- Contributed to [Mastodon](https://github.com/tootsuite/mastodon/pulls?q=author%3Aakihikodaki).
- Contributed to [rspec-sidekiq](https://github.com/philostler/rspec-sidekiq/pull/141).
- Developed Pawoo Music, a discontinued variant of Mastodon. I was responsible for a feature to generate a music video suitable for video-sharing websites like YouTube and Twitter. The feature had an interactive preview and the actual video was generated on the server.
  - Contributed to [PixiJS](https://github.com/pixijs/pixijs/pulls?q=is%3Apr+author%3Aakihikodaki+is%3Aclosed)
  - Contributed to [headless-gl](https://github.com/stackgl/headless-gl/pull/115)
  - I developed [the application](https://github.com/pixiv/musicvideo-generator) and determined the server configurations for accelerated graphics.
- Suggested and conducted an experiment to integrate Mastodon and [Matrix](https://matrix.org), although it was suspended before yielding any results and canceled later. Contributed to Matrix (https://github.com/matrix-org/matrix-react-sdk/pulls?q=is%3Apr+author%3Aakihikodaki+is%3Aclosed) in the process.

#### July 2018 - March 2019

I was relocated for developing [VRoid Studio](https://vroid.com/studio), a software to build humanoid 3D models without special expertise. For details of the application, see [a presentation given at _SA '21: SIGGRAPH Asia 2021 Real-Time Live!_](https://dl.acm.org/doi/10.1145/3478511.3491311)

My involvement began just before its first release. My focus was to improve the productivity of the team because the relocation was regarded as "temporal" in the first place.

- Constructed and maintained a CI infrastructure with [Unity](https://unity.com), Linux, and [GitLab CI](https://docs.gitlab.com/ee/ci/). GitLab CI was managed by a colleague so I wrote application-specific code and communicated with him for the integration.
- Designed and implemented [Mux](https://github.com/pixiv/Mux), a tool to build the UI with [XAML (eXtensible Application Markup Language)](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/xaml/xaml-basics/) and [data binding](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/app-fundamentals/data-binding/), and re-implemented the UI of VRoid Studio with Mux.
- Minor FLOSS contributions
  - Fixed many bugs in Xamarin.Forms' XAML processor used in Mux. https://github.com/xamarin/Xamarin.Forms/pulls?q=author%3Aakihikodaki+
  - Contributed to XR.Baboon https://github.com/inorton/XR.Baboon/pulls?q=is%3Apr+author%3Aakihikodaki+is%3Aclosed
  - Contributed to docfx https://github.com/dotnet/docfx/pulls?q=is%3Apr+author%3Aakihikodaki+is%3Aclosed
  - Contributed to UniVRM https://github.com/vrm-c/UniVRM/pull/21
  - Contributed to UniGLTF https://github.com/ousttrue/UniGLTF/pull/15

#### May 2019 - August 2019

I was employed as a full-time worker and had some training in April. Later, I joined the development of [VRoid Mobile](https://vroid.com/mobile), designed for more casual humanoid model creation and including an AR feature. I left the team just after its release.

- Designed the architecture of the application as a whole. (It was modeled as MVVM and integrated subsystems designed and implemented independently.)
- Clicked the "New Project" button of Unity and wrote the integration of different subsystems and many of its UI components (of course in Mux).
- Ported the CI infrastructure developed for VRoid Studio.
- Instructed other developers to enforce the application architecture and Mux best practices and to provide some generic programming advice. I intended to maintain the steady development until the release and after I left.
- Minor FLOSS contributions
  - Contributed to bitrise/steps-cache-push https://github.com/bitrise-steplib/steps-cache-push/pull/32
  - Contributed to better-apk-expansion https://github.com/auxility/better-apk-expansion/pull/16

#### September 2019 - October 2019

Technically I had never had the "On-the-Job Training", so I completed it by temporarily working for [ImageFlux](https://www.sakura.ad.jp/services/imageflux/) team.

[WebRTC bindings for .NET, mainly targeting Unity](https://github.com/pixiv/webrtc) are its results. The library avoids common pitfalls of such bindings like multi-platform support and garbage-collector awareness.

I also contributed to mono/sdb. https://github.com/mono/sdb/pull/58

#### November 2019 - February 2020

I was relocated to the [pixiv Sketch](https://sketch.pixiv.net/) team. pixiv Sketch is a social network where users can casually post drawings (i.e. it is totally fine to post incomplete works). It has drawing tools and a live broadcast feature.

I had no particular job to do, so I just did any technical things the others don't do.

pixiv Sketch had a *backend* server application providing RESTful APIs representing its resources and *frontends* providing the UI. Such a combination is called Backend-for-Frontend, or BFF. The backend was a Ruby on Rails application, and the frontends were Web, Android, and iOS applications.

I modified the WebRTC library for additional features on iOS like screen-casting with audio and an extra audio configuration. https://github.com/pixiv/webrtc

#### March 2020 - February 2021

The backend and the Web frontend of pixiv Sketch were assigned to me. I focused on reliability.

The backend interacted with [MySQL](https://www.mysql.com/) and Redis. The Web frontend provided the UI with React with its state managed with [Fluxible](https://fluxible.io).

- Contributed to ClusterWS/cWS https://github.com/ClusterWS/cWS/pull/35
- Debugged and patched Mozilla Firefox to fix CSRF. https://bugzilla.mozilla.org/show_bug.cgi?id=1605305

### March 2021

I became an unemployed FLOSS contributor again.

- QEMU https://gitlab.com/qemu-project/qemu/-/commits/master?author=Akihiko%20Odaki
- virglrenderer https://gitlab.freedesktop.org/virgl/virglrenderer/-/merge_requests?scope=all&utf8=✓&state=all&author_username=akihiko.odaki
- UTM https://github.com/utmapp/UTM/pull/2361
- Mutter https://gitlab.gnome.org/GNOME/mutter/-/merge_requests/1737

I'm working on QEMU on macOS. Especially I'm focusing on Virgil 3D, a bridge to expose host OpenGL to the guest, and Apple Silicon/M1.
https://gist.github.com/akihikodaki/87df4149e7ca87f18dc56807ec5a1bc5

### August 2022 - May 2025 - Daynix Computing Ltd.

I contributed to several open-source projects related to virtualization:

- QEMU https://gitlab.com/qemu-project/qemu/-/commits/master?author=Akihiko%20Odaki
- Linux https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/log/?qt=author&q=akihiko.odaki%40daynix.com
- AutoHCK https://github.com/HCK-CI/AutoHCK/commits/master/?author=akihikodaki
- AutoHCK-Installer https://github.com/HCK-CI/AutoHCK-Installer/commits/main/?author=akihikodaki
- HLK-Setup-Scripts https://github.com/HCK-CI/HLK-Setup-Scripts/commits/master/?author=akihikodaki
- rtoolsHCK https://github.com/HCK-CI/rtoolsHCK/commits/master/?author=akihikodaki
- meson https://github.com/mesonbuild/meson/commits/master/?author=akihikodaki
- b4 https://github.com/mricon/b4/commits/master/?author=akihikodaki
- DPDK Test Suite https://git.dpdk.org/tools/dts/log/?qt=author&q=akihiko.odaki%40daynix.com
- Linux Test Suite https://github.com/linux-test-project/ltp/commits/master/?author=akihikodaki
- libvirt https://gitlab.com/libvirt/libvirt/-/commits/master?author=Akihiko%20Odaki
- spice-common https://gitlab.freedesktop.org/spice/spice-common/-/commits/master?author=Akihiko%20Odaki
- spice-protocol https://gitlab.freedesktop.org/spice/spice-protocol/-/commits/master?author=Akihiko%20Odaki
- SPICE vd-agent https://gitlab.freedesktop.org/spice/win32/vd_agent/-/commits/master?author=Akihiko%20Odaki
- osinfo-db https://gitlab.com/libosinfo/osinfo-db/-/commits/main?author=Akihiko%20Odaki
- rubocop https://github.com/rubocop/rubocop/commits/master/?author=akihikodaki
- sorbet https://github.com/sorbet/sorbet/commits/master/?author=akihikodaki

I also made a few presentations:

- Reducing the Overhead of Network Virtualization: Software and Hardware Solutions, Linux Plumbers Conference 2024 https://lpc.events/event/18/contributions/1963/
- TCG Plugin in Practice: A Case of Microarchitecture Research, KVM Forum 2024 https://pretalx.com/kvm-forum-2024/talk/CYEGXD/
- Unleashing SR-IOV on Virtual Machines, KVM Forum 2024 https://pretalx.com/kvm-forum-2024/talk/ZA8KPD/

### April 2022 - Shioya Laboratory, Department of Creative Informatics, Graduate School of Information Science and Technology, The University of Tokyo

## My Name

### Akihiko (陽彦)

Akihiko is my given name. Aki (陽) means "sun". Hiko (彦) means, well, I don't know.

### Odaki 小田喜

Odaki is my family name. The literal meaning probably just doesn't make sense, but:
- O (小) means "small".
- Da (田) means "rice field".
- Ki (喜) means "happy".

So it may mean "I'm happy with a small rice field" or I don't know. Indeed, I prefer to get things done with a smaller code base.
