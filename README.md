English ⋅ Français

Warning
Don't use your main Apple account! Prefer a secondary Apple account.
I am NOT responsible if something happens with your Apple account.

What is this ?
Provision is a set of tools interracting with Apple servers on Linux.

It includes:

libprovision, a library used to register device on Apple servers.
anisette_server, an Anisette provisioning server for other software such as AltServer-Linux.
retrieve_headers, which registers the device with libprovision and returns in the terminal in JSON the headers to use to identify the device on future requests.
More precisely, libprovision registers the device to Apple servers and retrieve ADI data for your device. Once you logged in once with your machine, your machine is remembered as safe by Apple using this data Be careful to log-in only on trusted machines, and don't leak your ADI data, which is stored in ~/.adi/adi.pb.

There used to be a software called sideload-ipa listed here. The code has now been removed, as it was not working, and that I am now helping the development of SideServer (no official link yet), which reimplements the full AltServer with few more features.
