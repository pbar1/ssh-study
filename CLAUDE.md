I'm studying SSH implementations in pursuit of learning the best practices of how it is implemented so that I can implement from scratch myself. I've cloned a few repositories as Git submodules and want to compare and contrast them to extract knowledge.

Here is an index of the top level SSH repositories that we are studying:

- `libssh`: An SSH library in C with both client and server
- `libssh2`: An SSH library in C with client only
- `openssh-portable`: An SSH binary in C that is both client and server. This is essentially the SSH reference implementation.
- `russh`: An SSH library in Rust with both client and server
- `asyncssh`: An SSH library in Python with both client and server. It supports x509 certs.
- `go-crypto/ssh`: An SSH library in Go with both client and server
- `mina-sshd`: An SSH library in Java with both client and server. It is particularly well documented.
- `dropbear`: An SSH binary in C.
- `tinyssh`: An SSH binary in C. It is particularly minimal and may not even include TCP, and only uses static allocations.
- `wolfssh`: An SSH binary and library in C. It's embeddable, and supports x509 certs.

For comparison, these are some TLS libraries:

- `rustls`: A TLS library in Rust. This is not an SSH library, and is here for comparison sake for extracting Rust best practices.
- `fizz`: A TLS library in C++. This is not an SSH library, and is here for comparison sake for for its clean design such as its state machine and performance optimizations.

When I ask you for "for each" style questions, I want you to _actually_ do each of the repos I've mentioned here. Do not skip any of them in the interest of time.
