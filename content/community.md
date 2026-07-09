---
title: "The Community Build"
lede: "The Apptrix editor, free for open source developers. Same designer, same compiler, same native binaries."
---

## What you get

The Community Build is not a demo or a feature-gated trial. It is the Apptrix
application, with two server-backed capabilities removed.

- **The visual designer.** Compose interfaces from Fyne's widget set plus the
  Apptrix components, with layout, theming and data binding handled visually.
- **Real native output.** Your project compiles to a native binary — no web view,
  no embedded runtime.
- **Every target platform.** macOS, Windows, Linux, iOS and Android from a single
  project.
- **Local, offline, private.** The editor runs on your machine. Your project
  never leaves it. No account, no sign-in, no telemetry you did not ask for.
- **An escape hatch.** The output is Go. When the visual layer stops being the
  clearest way to say something, write the code.

## What it does not include

Two things in the commercial product depend on infrastructure we run, and so are
not part of the Community Build:

**AI assistance.** The commercial platform embeds local inference so an assistant
can help you build without token costs or sending your project to a third party.
That model tooling is not in the Community Build.

**The hosted build server.** Apptrix.ai can cross-compile and sign your app for
every platform in the cloud. In the Community Build you build locally, which
means shipping to iOS or Android requires the usual platform toolchains
installed on your own machine — Xcode, the Android SDK and NDK. Desktop targets
need only a Go toolchain and a C compiler.

Everything else — the designer, the component library, the compiler, the native
output — is the same software.

## Who it is for

The Community Build is licensed for **open source work**. If what you build is
released under an open source licence, you may use it freely, with no fee and no
registration.

Building something proprietary, or want the AI and cloud builds? The commercial
platform is at [apptrix.ai](https://apptrix.ai).

Read the [Community License](/license/) for the precise terms, then
[download a build](/download/).

## Getting help

Apptrix development happens alongside the Fyne community. For questions about
the toolkit itself, the [Fyne documentation](https://docs.fyne.io) is the place
to start. For the Community Build, reach us at <hello@apptrix.ai>.
