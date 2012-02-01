# iOS-compatible open source .framework libraries

Om nom nom.

## Why?

Because you can include these frameworks into either ARC or non-ARC projects
and you don't have to worry about whether or not their ARC-ness matches your
project's ARC-ness.

## Isn't that what static libraries are for?

Yeah, you can do that too, but this way, you can see each library's header files
neatly packaged inside the XXX.framework entry in Xcode's project sidebar.  You
don't have to add the headers manually.

## Authors

bryn austin bellomy (all I did was build these as .framework
libraries -- no code was changed whatsoever)
pokeb (for [ASIHTTPRequest][ASIHTTPRequest])
robbiehanson (for [GCDAsyncSocket][GCDAsyncSocket])
johnezang (for [JSONKit][JSONKit])
samvermette (for [SVProgressHUD][SVProgressHUD])

[ASIHTTPRequest]: https://github.com/pokeb/asi-http-request
[GCDAsyncSocket]: https://github.com/robbiehanson/CocoaAsyncSocket
[JSONKit]: https://github.com/johnezang/JSONKit
[SVProgressHUD]: https://github.com/samvermette/SVProgressHUD
