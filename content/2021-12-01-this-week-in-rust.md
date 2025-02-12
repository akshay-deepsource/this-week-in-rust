Title: This Week in Rust 419
Number: 419
Date: 2021-12-01
Category: This Week in Rust

Hello and welcome to another issue of *This Week in Rust*!
[Rust](http://rust-lang.org) is a programming language empowering everyone to build reliable and efficient software.
This is a weekly summary of its progress and community.
Want something mentioned? Tweet us at [@ThisWeekInRust](https://twitter.com/ThisWeekInRust) or [send us a pull request](https://github.com/rust-lang/this-week-in-rust).
Want to get involved? [We love contributions](https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md).

*This Week in Rust* is openly developed [on GitHub](https://github.com/rust-lang/this-week-in-rust).
If you find any errors in this week's issue, [please submit a PR](https://github.com/rust-lang/this-week-in-rust/pulls).

## Updates from Rust Community

### Official
* [In response to the moderation team resignation](https://blog.rust-lang.org/inside-rust/2021/11/25/in-response-to-the-moderation-team-resignation.html)
* [1.57.0 pre-release testing](https://blog.rust-lang.org/inside-rust/2021/11/30/1.57.0-prerelease.html)

### Project/Tooling Updates
* [Rust Analyzer Changelog #105](https://rust-analyzer.github.io//thisweek/2021/11/29/changelog-105.html)
* [Black Hat Week (Black Hat Rust is out 🍾)](https://kerkour.com/black-hat-rust-week-2021/)
* [SixtyFPS (GUI crate): Changelog for 28th of November 2021 – 0.1.15 Release](https://sixtyfps.io/thisweek/2021-11-29.html)
* [This week in Databend #18: an elastic and reliable cloud warehouse](https://weekly.databend.rs/2021-12-01-databend-weekly/)
* [Wasmer 2.1](https://wasmer.io/posts/wasmer-2.1)
* [Wyrcan ~ The Container Bootloader](https://gitlab.com/wyrcan/wyrcan/-/tree/v1.0.0)

### Observations/Thoughts
* [Do we Really Need Undefined Behavior?](https://www.ralfj.de/blog/2021/11/24/ub-necessary.html)
* [Box Pointers in Rust make recursive types possible](https://blog.knoldus.com/box-pointers-in-rust-make-recursive-types-possible/)
* [Notes On Module System](https://matklad.github.io//2021/11/27/notes-on-module-system.html)
* [A prioritised micro-batch scheduler in rust](https://njk.onl/blog/gaffer.html)
* [Go footguns: Go Defer and Rust Drop](https://dev.to/mark_saward/go-footguns-go-defer-and-rust-drop-17af)
* [LLVM internals, part 4: attributes and attribute groups](https://blog.yossarian.net/2021/11/29/LLVM-internals-part-4-attributes-and-attribute-groups)
* [Implementing Raft for Browsers with Rust and WebRTC](https://eevans.co/blog/wraft/)
* [Hubris and Humility](https://oxide.computer/blog/hubris-and-humility)
* [ZH] [Zero-Cost Abstractions in Rust](https://dev.to/daniel1in/zero-cost-abstractions-in-rust-5e41)
* [audio] [Game Development with Herbert Wolverson](https://rustacean-station.org/episode/048-herbert-wolverson/)
* [video] [Rust Linz, November 2021 - Advent of Code by Rainer Stropek with Fred Morcos](https://www.youtube.com/watch?v=bejThbzAYOA)
* [video] [Rust Linz, November 2021 - Serde Shenanigans by Armin Ronacher](https://www.youtube.com/watch?v=UhZGYS13twc)
* [video] [Rust Linz, November 2021 - WebAssembly beyond the browser by Thorsten Hans](https://www.youtube.com/watch?v=o6qe4lw9-8c)
* [video] [Rust 2021 Edition Explained](https://www.youtube.com/watch?v=uIeIBlB0JFw)
* [video] [Mats Kindahl: A C++ programmer's view on Rust](https://www.youtube.com/watch?v=DGbsHENouy4)

### Rust Walkthroughs
* [Using WebAssembly (created in Rust) for Fast React Components](https://www.joshfinnie.com/blog/using-webassembly-created-in-rust-for-fast-react-components/)
* [Speed up Rust Builds with Cachepot](https://kflansburg.com/posts/rust-cachepot/)
* [Rena’s Memory Model](https://veera.app/rena%27s_memory_model.html)
* [How to Build a Note Taking Command Line Application With Rust: Part 1](https://levelup.gitconnected.com/how-to-build-a-note-taking-command-line-application-with-rust-part-1-34b9cd5be6b9)
* [Rust Project: Ping Pong Game](https://phychic-owl.medium.com/rust-project-ping-pong-game-665766cc45ed)
* [Learn Rust Programming Course – Interactive Rust Language Tutorial on Repl.it](https://www.freecodecamp.org/news/rust-in-replit/)
* [Position Independent Shellcodes in Rust (PIC)](https://kerkour.com/rust-position-independent-shellcode/)
* [Run Your Rust Games in a Browser](https://medium.com/pragmatic-programmers/run-your-rust-games-in-a-browser-ceea86b04616)
* [Git Internals part 2: packfiles](https://dev.to/calebsander/git-internals-part-2-packfiles-1jg8)
* [Building a simple on-chain point of sale with Solana, Anchor and React](https://dev.to/fndomendez/building-a-simple-on-chain-point-of-sale-with-solana-anchor-and-react-859)
* [Checking Unused Dependencies in a Rust Project with Github Actions](https://erayerdin.com/checking-unused-dependencies-in-a-rust-project-with-github-actions-ckwm3yov901cwlvs1h48z54xi)
* [video] [rg3d - live coding session #3](https://www.youtube.com/watch?v=U_XGkDZcV1k)
* [video] [The Ray Tracer Challenge - 022 - Planes](https://www.youtube.com/watch?v=4y1aRPiH9Ko)
* [PL] [video] [Rust na raz #2: Ugliest workaround for unsafe](https://www.youtube.com/watch?v=q2lWUmAKsVQ)

### Miscellaneous
* [Can Rust save the planet? Why, and why not](https://www.theregister.com/2021/11/30/aws_reinvent_rust/)
* [4x smaller, 50x faster](https://blog.asciinema.org/post/smaller-faster/)
* [PT] [Esta-Semana-Em-Rust #418](https://github.com/luisvonmuller/Esta-Semana-Em-Rust/blob/main/%23418.md)
* [video] [RCIG Sync-up call #6](https://www.youtube.com/watch?v=pQmL71xAzIk)

## Crate of the Week

This week's crate is [poem-openapi](https://crates.io/crates/poem-openapi), a framework to implement OpenAPI services.

llogiq is very pleased with his suggestion.

[Please submit your suggestions and votes for next week][submit_crate]!

[submit_crate]: https://users.rust-lang.org/t/crate-of-the-week/2704

## Call for Participation

Always wanted to contribute to open-source projects but didn't know where to start?
Every week we highlight some tasks from the Rust community for you to pick and get started!

Some of these tasks may also have mentors available, visit the task page for more information.

* [rusty-celery is looking for maintainers](https://github.com/rusty-celery/rusty-celery)

**Ockam**

* [Move the ockam_vault_core create into ockam_core](https://github.com/ockam-network/ockam/issues/2288)
* [Move the ockam_key_exchange_core create into ockam_core](https://github.com/ockam-network/ockam/issues/2291)
* [Delete the ockam_node_no_std crate](https://github.com/ockam-network/ockam/issues/2287)

If you are a Rust project owner and are looking for contributors, please submit tasks [here][guidelines].

[guidelines]: https://users.rust-lang.org/t/twir-call-for-participation/4821

## Updates from the Rust Project

244 pull requests were [merged in the last week][merged]

[merged]: https://github.com/search?q=is%3Apr+org%3Arust-lang+is%3Amerged+merged%3A2021-11-22..2021-11-29

* [add codegen option for using LLVM stack smash protection](https://github.com/rust-lang/rust/pull/84197)
* [do not use atomic reads on platforms without atomic support in LLVM](https://github.com/rust-lang/compiler-builtins/pull/442)
* [diagnostic tweaks](https://github.com/rust-lang/rust/pull/85102)
* [chalk: introduce `Folder::Error`](https://github.com/rust-lang/chalk/pull/709)
* [miri: more portable SIMD: rem, shl, shr](https://github.com/rust-lang/miri/pull/1923)
* [fix ICE due to out-of-bounds statement index when reporting borrowck error](https://github.com/rust-lang/rust/pull/91212)
* [fix ICE when lowering `trait A where for<'a> Self: 'a`](https://github.com/rust-lang/rust/pull/91308)
* [faster `Layout::array`](https://github.com/rust-lang/rust/pull/91246)
* [make `TypeFolder::fold_*` return `Result`](https://github.com/rust-lang/rust/pull/91230)
* [partially stabilize `duration_consts_2`](https://github.com/rust-lang/rust/pull/89542)
* [stabilize `nonzero_is_power_of_two`](https://github.com/rust-lang/rust/pull/91301)
* [stabilize some `MaybeUninit` behavior as const](https://github.com/rust-lang/rust/pull/90896)
* [add fast path to `is_descendant_of`](https://github.com/rust-lang/rust/pull/91043)
* [futures: remove dependency on proc-macro-hack](https://github.com/rust-lang/futures-rs/pull/2520)
* [cargo: improve unused patch message when source URLs mismatched](https://github.com/rust-lang/cargo/pull/10130)
* [clippy: add `needless_late_init` lint](https://github.com/rust-lang/rust-clippy/pull/7995)
* [clippy: add more descriptive help info for `needless_question_mark`](https://github.com/rust-lang/rust-clippy/pull/8028)
* [clippy: fix false positive on `if_then_some_else_none` with early return](https://github.com/rust-lang/rust-clippy/pull/7980)
* [clippy: improve `strlen_on_c_string`](https://github.com/rust-lang/rust-clippy/pull/8001)
* [clippy: extend `non_ascii_literal` to cover chars](https://github.com/rust-lang/rust-clippy/pull/8034)
* [clippy: apply iter_cloned_collect to collect() using copied()](https://github.com/rust-lang/rust-clippy/pull/8006)
* [rustdoc: avoid documenting top-level private imports](https://github.com/rust-lang/rust/pull/91094)
* [rustfmt: fix: do not wrap reference-style doc links](https://github.com/rust-lang/rustfmt/pull/5096)
* [rustfmt: maintain more AST info when formatting a RHS](https://github.com/rust-lang/rustfmt/pull/5113)

### Rust Compiler Performance Triage

Overall, many changes this week, but overall an improvement on multiple benchmarks over
the week from a number of pull requests dedicated to optimizations of certain
patterns. We are still seeing a large number of spurious changes due to
[rustc-perf#1105](https://github.com/rust-lang/rustc-perf/issues/1105), which
has yet to be addressed.

Triage done by **@simulacrum**.
Revision range: [22c2d9d..1c028783](https://perf.rust-lang.org/?start=22c2d9ddbf356bcdb718e88ca6ee3665e1e42690&end=1c0287830e0fb3c4007afea2819ba03766da6e9c&absolute=false&stat=instructions%3Au)

4 Regressions, 4 Improvements, 9 Mixed; 5 of them in rollups
41 comparisons made in total

[Full report here](https://github.com/rust-lang/rustc-perf/blob/master/triage/2021-11-30.md)

### [Approved RFCs](https://github.com/rust-lang/rfcs/commits/master)

Changes to Rust follow the Rust [RFC (request for comments) process](https://github.com/rust-lang/rfcs#rust-rfcs). These
are the RFCs that were approved for implementation this week:

* *No RFCs were approved this week.*

### Final Comment Period

Every week [the team](https://www.rust-lang.org/team.html) announces the
'final comment period' for RFCs and key PRs which are reaching a
decision. Express your opinions now.

#### [RFCs](https://github.com/rust-lang/rfcs/labels/final-comment-period)

* *No RFCs entered final comment period this week.*

#### [Tracking Issues & PRs](https://github.com/rust-lang/rust/labels/final-comment-period)

* [disposition: merge] [rustdoc: accept --out-dir and soft-deprecate --output](https://github.com/rust-lang/rust/issues/91260)
* [disposition: merge] [Tracking Issue for #![feature(available_parallelism)]](https://github.com/rust-lang/rust/issues/74479)

### [New RFCs](https://github.com/rust-lang/rfcs/pulls)

* [RFC: Attributes in function return type position](https://github.com/rust-lang/rfcs/pull/3201)
* [RFC: proc macro include!](https://github.com/rust-lang/rfcs/pull/3200)
* [RFC: Unsafe Lifetime](https://github.com/rust-lang/rfcs/pull/3199)

## Upcoming Events

Rusty Events between 12/01-12/15 🦀

### Online

* [December 3, 2021 | New York City, NY, US | **Getting started in aerospace with Rust 🦀** | NewSpace NYC](https://www.meetup.com/NewSpace-NYC/events/282320805).
* [December 7, 2021 | Buffalo, NY, US | **First Tuesdays** | Buffalo Rust Meetup](https://www.meetup.com/Buffalo-Rust-Meetup/events/281833990/)
* [December 8, 2021 | Los Gatos, CA, US | **Book #24 - Rust for Rustaceans - Chapter 1** | Los Gatos Reading Group](https://www.meetup.com/Los-Gatos-Rust-Reading-Group/events/281966245)
* [December 8, 2021 | Los Angeles, CA, US | **Rust Computer Vision Project with Geordon Worley** | Rust Los Angeles](https://www.meetup.com/Rust-Los-Angeles/events/281944671/)
* [December 8, 2021 | Stuttgart, DE | **Rust-Meetup** | Rust Community Stuttgart](https://www.meetup.com/Rust-Community-Stuttgart/events/282009864)
* [December 10, 2021 | Chicago, IL, US | **8LU Keynote by Eric Smith - Write Your Game in Rust!** | 8th Light University](https://www.meetup.com/8th-light-university/events/282381279)
* [December 14, 2021 | Seattle, WA, US | **Monthly Meetup** | Seattle Rust Meetup](https://www.meetup.com/Seattle-Rust-Meetup/events/281875277)

### North America

* [December 8, 2021 | Atlanta, GA, US | **Grab a beer with fellow Rustaceans** | Rust Atlanta](https://www.meetup.com/Rust-ATL/events/lhpkmsyccqblb/)

### Europe

* [December 3, 2021 | Moscow, RU | **Rust Con** | RustCon.ru](https://rustcon.ru)

If you are running a Rust event please add it to the [calendar] to get
it mentioned here. Please remember to add a link to the event too.
Email the [Rust Community Team][community] for access.

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[community]: mailto:community-team@rust-lang.org

# Rust Jobs

**Tangram**

* [Rust Developer (Remote)](https://www.tangram.dev/jobs)

**Flaps**

* [Rust developer & distributed systems (Remote)](https://www.linkedin.com/jobs/view/2818309506/)

**CoBloX**

* [Software Engineer (Sydney, AU or Remote with 5h overlap with UTC+10 (AEST)](https://comit.network/blog/2021/03/01/we-are-hiring/)

**Globelise**

* [Backend Engineer (Remote)](https://www.techinasia.com/jobs/75de79c7-492d-4493-b247-1315979227bc)

**Bionaut Labs**

* [Embedded Software Engineer (Senior) (Los Angeles, CA, US)](https://www.indeed.com/viewjob?jk=9cda3e340d35e515)
* [Embedded Software Engineer (Junior) (Los Angeles, CA)](https://www.indeed.com/viewjob?jk=5b14daa53cc356d2)

**Massa Labs**

* [Several Rust Engineering Positions Available](https://massa.net/jobs.html)

*Tweet us at [@ThisWeekInRust](https://twitter.com/ThisWeekInRust) to get your job offers listed here!*

# Quote of the Week

> The design of the safe/unsafe split means that there is an asymmetric trust relationship between Safe and Unsafe Rust. Safe Rust inherently has to trust that any Unsafe Rust it touches has been written correctly. On the other hand, Unsafe Rust cannot trust Safe Rust without care.
>
> As an example, Rust has the [`PartialOrd`](https://doc.rust-lang.org/nightly/std/cmp/trait.PartialOrd.html) and [`Ord`](https://doc.rust-lang.org/nightly/std/cmp/trait.Ord.html) traits to differentiate between types which can "just" be compared, and those that provide a "total" ordering (which basically means that comparison behaves reasonably).
>
> [`BTreeMap`](https://doc.rust-lang.org/nightly/std/collections/struct.BTreeMap.html) doesn't really make sense for partially-ordered types, and so it requires that its keys implement `Ord` . However, `BTreeMap` has Unsafe Rust code inside of its implementation. Because it would be unacceptable for a sloppy `Ord` implementation (which is Safe to write) to cause Undefined Behavior, the Unsafe code in BTreeMap must be written to be robust against `Ord` implementations which aren't actually total — even though that's the whole point of requiring `Ord` .

– [Gankra citing the Rustonomicon on github](https://github.com/rust-lang/rfcs/pull/3197#issuecomment-976032253)

Thanks to [robin](https://users.rust-lang.org/t/twir-quote-of-the-week/328/1144) for the suggestion!

[Please submit quotes and vote for next week!](https://users.rust-lang.org/t/twir-quote-of-the-week/328)

*This Week in Rust is edited by: [nellshamrell](https://github.com/nellshamrell), [llogiq](https://github.com/llogiq), [cdmistman](https://github.com/cdmistman), [ericseppanen](https://github.com/ericseppanen), [extrawurst](https://github.com/extrawurst), [andrewpollack](https://github.com/andrewpollack), [U007D](https://github.com/U007D), [kolharsam](https://github.com/kolharsam), [joelmarcey](https://github.com/joelmarcey), [marriannegoldin](https://github.com/marriannegoldin).*

*Email list hosting is sponsored by [The Rust Foundation](https://foundation.rust-lang.org/)*

<small>[Discuss on r/rust](https://www.reddit.com/r/rust/comments/r6wnr7/this_week_in_rust_419/)</small>
