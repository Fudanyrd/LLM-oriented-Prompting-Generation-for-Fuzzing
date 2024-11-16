archive
tar
Package tar implements access to tar archives.
zip
Package zip provides support for reading and writing ZIP archives.
bufio
Package bufio implements buffered I/O. It wraps an io.Reader or io.Writer object, creating another object (Reader or Writer) that also implements the interface but provides buffering and some help for textual I/O.
builtin
Package builtin provides documentation for Go's predeclared identifiers.
bytes
Package bytes implements functions for the manipulation of byte slices.
compress
bzip2
Package bzip2 implements bzip2 decompression.
flate
Package flate implements the DEFLATE compressed data format, described in RFC 1951.
gzip
Package gzip implements reading and writing of gzip format compressed files, as specified in RFC 1952.
lzw
Package lzw implements the Lempel-Ziv-Welch compressed data format, described in T. A. Welch, “A Technique for High-Performance Data Compression”, Computer, 17(6) (June 1984), pp 8-19.
zlib
Package zlib implements reading and writing of zlib format compressed data, as specified in RFC 1950.
container
heap
Package heap provides heap operations for any type that implements heap.Interface.
list
Package list implements a doubly linked list.
ring
Package ring implements operations on circular lists.
context
Package context defines the Context type, which carries deadlines, cancellation signals, and other request-scoped values across API boundaries and between processes.
crypto
Package crypto collects common cryptographic constants.
aes
Package aes implements AES encryption (formerly Rijndael), as defined in U.S. Federal Information Processing Standards Publication 197.
cipher
Package cipher implements standard block cipher modes that can be wrapped around low-level block cipher implementations.
des
Package des implements the Data Encryption Standard (DES) and the Triple Data Encryption Algorithm (TDEA) as defined in U.S. Federal Information Processing Standards Publication 46-3.
dsa
Package dsa implements the Digital Signature Algorithm, as defined in FIPS 186-3.
ecdh
Package ecdh implements Elliptic Curve Diffie-Hellman over NIST curves and Curve25519.
ecdsa
Package ecdsa implements the Elliptic Curve Digital Signature Algorithm, as defined in FIPS 186-4 and SEC 1, Version 2.0.
ed25519
Package ed25519 implements the Ed25519 signature algorithm.
elliptic
Package elliptic implements the standard NIST P-224, P-256, P-384, and P-521 elliptic curves over prime fields.
hmac
Package hmac implements the Keyed-Hash Message Authentication Code (HMAC) as defined in U.S. Federal Information Processing Standards Publication 198.
md5
Package md5 implements the MD5 hash algorithm as defined in RFC 1321.
rand
Package rand implements a cryptographically secure random number generator.
rc4
Package rc4 implements RC4 encryption, as defined in Bruce Schneier's Applied Cryptography.
rsa
Package rsa implements RSA encryption as specified in PKCS #1 and RFC 8017.
sha1
Package sha1 implements the SHA-1 hash algorithm as defined in RFC 3174.
sha256
Package sha256 implements the SHA224 and SHA256 hash algorithms as defined in FIPS 180-4.
sha512
Package sha512 implements the SHA-384, SHA-512, SHA-512/224, and SHA-512/256 hash algorithms as defined in FIPS 180-4.
subtle
Package subtle implements functions that are often useful in cryptographic code but require careful thought to use correctly.
tls
Package tls partially implements TLS 1.2, as specified in RFC 5246, and TLS 1.3, as specified in RFC 8446.
x509
Package x509 implements a subset of the X.509 standard.
x509/pkix
Package pkix contains shared, low level structures used for ASN.1 parsing and serialization of X.509 certificates, CRL and OCSP.
database
sql
Package sql provides a generic interface around SQL (or SQL-like) databases.
sql/driver
Package driver defines interfaces to be implemented by database drivers as used by package sql.
debug
buildinfo
Package buildinfo provides access to information embedded in a Go binary about how it was built.
dwarf
Package dwarf provides access to DWARF debugging information loaded from executable files, as defined in the DWARF 2.0 Standard at http://dwarfstd.org/doc/dwarf-2.0.0.pdf.
elf
Package elf implements access to ELF object files.
gosym
Package gosym implements access to the Go symbol and line number tables embedded in Go binaries generated by the gc compilers.
macho
Package macho implements access to Mach-O object files.
pe
Package pe implements access to PE (Microsoft Windows Portable Executable) files.
plan9obj
Package plan9obj implements access to Plan 9 a.out object files.
embed
Package embed provides access to files embedded in the running Go program.
encoding
Package encoding defines interfaces shared by other packages that convert data to and from byte-level and textual representations.
ascii85
Package ascii85 implements the ascii85 data encoding as used in the btoa tool and Adobe's PostScript and PDF document formats.
asn1
Package asn1 implements parsing of DER-encoded ASN.1 data structures, as defined in ITU-T Rec X.690.
base32
Package base32 implements base32 encoding as specified by RFC 4648.
base64
Package base64 implements base64 encoding as specified by RFC 4648.
binary
Package binary implements simple translation between numbers and byte sequences and encoding and decoding of varints.
csv
Package csv reads and writes comma-separated values (CSV) files.
gob
Package gob manages streams of gobs - binary values exchanged between an Encoder (transmitter) and a Decoder (receiver).
hex
Package hex implements hexadecimal encoding and decoding.
json
Package json implements encoding and decoding of JSON as defined in RFC 7159.
pem
Package pem implements the PEM data encoding, which originated in Privacy Enhanced Mail.
xml
Package xml implements a simple XML 1.0 parser that understands XML name spaces.
errors
Package errors implements functions to manipulate errors.
expvar
Package expvar provides a standardized interface to public variables, such as operation counters in servers.
flag
Package flag implements command-line flag parsing.
fmt
Package fmt implements formatted I/O with functions analogous to C's printf and scanf.
go
ast
Package ast declares the types used to represent syntax trees for Go packages.
build
Package build gathers information about Go packages.
build/constraint
Package constraint implements parsing and evaluation of build constraint lines.
constant
Package constant implements Values representing untyped Go constants and their corresponding operations.
doc
Package doc extracts source code documentation from a Go AST.
doc/comment
Package comment implements parsing and reformatting of Go doc comments, (documentation comments), which are comments that immediately precede a top-level declaration of a package, const, func, type, or var.
format
Package format implements standard formatting of Go source.
importer
Package importer provides access to export data importers.
parser
Package parser implements a parser for Go source files.
printer
Package printer implements printing of AST nodes.
scanner
Package scanner implements a scanner for Go source text.
token
Package token defines constants representing the lexical tokens of the Go programming language and basic operations on tokens (printing, predicates).
types
Package types declares the data types and implements the algorithms for type-checking of Go packages.
hash
Package hash provides interfaces for hash functions.
adler32
Package adler32 implements the Adler-32 checksum.
crc32
Package crc32 implements the 32-bit cyclic redundancy check, or CRC-32, checksum.
crc64
Package crc64 implements the 64-bit cyclic redundancy check, or CRC-64, checksum.
fnv
Package fnv implements FNV-1 and FNV-1a, non-cryptographic hash functions created by Glenn Fowler, Landon Curt Noll, and Phong Vo.
maphash
Package maphash provides hash functions on byte sequences.
html
Package html provides functions for escaping and unescaping HTML text.
template
Package template (html/template) implements data-driven templates for generating HTML output safe against code injection.
image
Package image implements a basic 2-D image library.
color
Package color implements a basic color library.
color/palette
Package palette provides standard color palettes.
draw
Package draw provides image composition functions.
gif
Package gif implements a GIF image decoder and encoder.
jpeg
Package jpeg implements a JPEG image decoder and encoder.
png
Package png implements a PNG image decoder and encoder.
index
suffixarray
Package suffixarray implements substring search in logarithmic time using an in-memory suffix array.
io
Package io provides basic interfaces to I/O primitives.
fs
Package fs defines basic interfaces to a file system.
ioutil
Package ioutil implements some I/O utility functions.
log
Package log implements a simple logging package.
syslog
Package syslog provides a simple interface to the system log service.
math
Package math provides basic constants and mathematical functions.
big
Package big implements arbitrary-precision arithmetic (big numbers).
bits
Package bits implements bit counting and manipulation functions for the predeclared unsigned integer types.
cmplx
Package cmplx provides basic constants and mathematical functions for complex numbers.
rand
Package rand implements pseudo-random number generators unsuitable for security-sensitive work.
mime
Package mime implements parts of the MIME spec.
multipart
Package multipart implements MIME multipart parsing, as defined in RFC 2046.
quotedprintable
Package quotedprintable implements quoted-printable encoding as specified by RFC 2045.
net
Package net provides a portable interface for network I/O, including TCP/IP, UDP, domain name resolution, and Unix domain sockets.
http
Package http provides HTTP client and server implementations.
http/cgi
Package cgi implements CGI (Common Gateway Interface) as specified in RFC 3875.
http/cookiejar
Package cookiejar implements an in-memory RFC 6265-compliant http.CookieJar.
http/fcgi
Package fcgi implements the FastCGI protocol.
http/httptest
Package httptest provides utilities for HTTP testing.
http/httptrace
Package httptrace provides mechanisms to trace the events within HTTP client requests.
http/httputil
Package httputil provides HTTP utility functions, complementing the more common ones in the net/http package.
http/pprof
Package pprof serves via its HTTP server runtime profiling data in the format expected by the pprof visualization tool.
mail
Package mail implements parsing of mail messages.
netip
Package netip defines an IP address type that's a small value type.
rpc
Package rpc provides access to the exported methods of an object across a network or other I/O connection.
rpc/jsonrpc
Package jsonrpc implements a JSON-RPC 1.0 ClientCodec and ServerCodec for the rpc package.
smtp
Package smtp implements the Simple Mail Transfer Protocol as defined in RFC 5321.
textproto
Package textproto implements generic support for text-based request/response protocols in the style of HTTP, NNTP, and SMTP.
url
Package url parses URLs and implements query escaping.
os
Package os provides a platform-independent interface to operating system functionality.
exec
Package exec runs external commands.
signal
Package signal implements access to incoming signals.
user
Package user allows user account lookups by name or id.
path
Package path implements utility routines for manipulating slash-separated paths.
filepath
Package filepath implements utility routines for manipulating filename paths in a way compatible with the target operating system-defined file paths.
plugin
Package plugin implements loading and symbol resolution of Go plugins.
reflect
Package reflect implements run-time reflection, allowing a program to manipulate objects with arbitrary types.
regexp
Package regexp implements regular expression search.
syntax
Package syntax parses regular expressions into parse trees and compiles parse trees into programs.
runtime
Package runtime contains operations that interact with Go's runtime system, such as functions to control goroutines.
cgo
Package cgo contains runtime support for code generated by the cgo tool.
coverage
debug
Package debug contains facilities for programs to debug themselves while they are running.
metrics
Package metrics provides a stable interface to access implementation-defined metrics exported by the Go runtime.
pprof
Package pprof writes runtime profiling data in the format expected by the pprof visualization tool.
race
Package race implements data race detection logic.
trace
Package trace contains facilities for programs to generate traces for the Go execution tracer.
sort
Package sort provides primitives for sorting slices and user-defined collections.
strconv
Package strconv implements conversions to and from string representations of basic data types.
strings
Package strings implements simple functions to manipulate UTF-8 encoded strings.
sync
Package sync provides basic synchronization primitives such as mutual exclusion locks.
atomic
Package atomic provides low-level atomic memory primitives useful for implementing synchronization algorithms.
syscall
Package syscall contains an interface to the low-level operating system primitives.
js
Package js gives access to the WebAssembly host environment when using the js/wasm architecture.
testing
Package testing provides support for automated testing of Go packages.
fstest
Package fstest implements support for testing implementations and users of file systems.
iotest
Package iotest implements Readers and Writers useful mainly for testing.
quick
Package quick implements utility functions to help with black box testing.
text
scanner
Package scanner provides a scanner and tokenizer for UTF-8-encoded text.
tabwriter
Package tabwriter implements a write filter (tabwriter.Writer) that translates tabbed columns in input into properly aligned text.
template
Package template implements data-driven templates for generating textual output.
template/parse
Package parse builds parse trees for templates as defined by text/template and html/template.
time
Package time provides functionality for measuring and displaying time.
tzdata
Package tzdata provides an embedded copy of the timezone database.
unicode
Package unicode provides data and functions to test some properties of Unicode code points.
utf16
Package utf16 implements encoding and decoding of UTF-16 sequences.
utf8
Package utf8 implements functions and constants to support text encoded in UTF-8.
unsafe
Package unsafe contains operations that step around the type safety of Go programs.