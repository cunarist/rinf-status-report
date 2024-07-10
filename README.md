# Rinf Status Report

In January 2024, the developers of [flutter_rust_bridge](https://github.com/fzyzcjy/flutter_rust_bridge) (FRB) pointed out that [Rinf](https://github.com/cunarist/rinf) had copied a significant amount of its code, raising concerns within the community. This article aims to clarify the current independence of Rinf's code to the Rust and Flutter communities.

We acknowledge that it was a mistake to copy FRB's code and remove the license texts that clarified the origin of the code. We accept all the criticism from FRB developers and the community. We sincerely apologize to FRB developers and the open-source community. After receiving feedback, we immediately began working to resolve this issue.

While acknowledging the judgments from FRB detailed in the posts below, this report focuses on demonstrating that Rinf no longer contains any copied code.

### 01/08/2024

FRB reported that Rinf had copied a significant amount of its code. Many developers in the Rust and Flutter communities have been discussing and criticizing various issues related to Rinf, including those concerning ethics and licensing.

FRB also created a [Git diff](https://github.com/fzyzcjy/appendix_2024/compare/cmp_frb...cmp_rinf?expand=1) link showing how Rinf had copied code from their repository.

- [Reddit Rust Post](https://www.reddit.com/r/rust/comments/191b2to/rinf_copies_a_lot_from_flutter_rust_bridge_but/)
- [Reddit FlutterDev Post](https://www.reddit.com/r/FlutterDev/comments/191b3k7/rinf_copies_a_lot_from_flutter_rust_bridge_but/)
- [GitHub Appendix](https://github.com/fzyzcjy/appendix_2024)
- [Hacker News](https://news.ycombinator.com/item?id=38900829)
- [Diff Image 1](https://raw.githubusercontent.com/fzyzcjy/appendix_2024/master/images/rinf_vs_frb.png)
- [Diff Image 2](https://raw.githubusercontent.com/fzyzcjy/appendix_2024/master/images/rinf_vs_itself.png)

![Image](https://github.com/cunarist/rinf-status-report/assets/66480156/484e374b-fd52-4476-8212-d4c06a56a4c3)

### 01/10/2024

We have removed all the code copied from FRB, leaving only the original code of Rinf in the repository while rewriting the copied parts. The PR for removing all the copied code can be seen [here](https://github.com/cunarist/rinf/pull/262). We have also posted about our mistake and expressed our apologies.

- [Reddit Post](https://www.reddit.com/r/rust/comments/192n4ej/rinf_did_copy_a_lot_from_flutter_rust_bridge/)

![Image](https://github.com/cunarist/rinf-status-report/assets/66480156/296a3544-5d7c-4cac-a455-5f5095a88218)

### 07/10/2024

FRB has come a long way since then, publishing a drastically improved version v2. Rinf has also released version 6, introducing many changes without any copied code.

- [FRB on pub.dev](https://pub.dev/packages/flutter_rust_bridge)
- [Rinf on pub.dev](https://pub.dev/packages/rinf)

For those who are still concerned, the current Rinf code can be seen at the links below. We assure you that there is no code copied from FRB anymore.

- [Rinf Flutter FFI Plugin](https://github.com/cunarist/rinf/tree/main/flutter_ffi_plugin/lib)
- [Rinf Rust Crate](https://github.com/cunarist/rinf/tree/main/rust_crate)

We appreciate the feedback from the community and remain committed to maintaining the integrity of open-source development. Moving forward, we aim to contribute positively and ensure that Rinf continues to grow independently and ethically. Thank you for your understanding and support.
