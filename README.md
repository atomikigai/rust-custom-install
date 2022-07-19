## rust-custom-install
### How to custom install Rust Language Windows

Open windows powershell and set this variables:
[Environment]::SetEnvironmentVariable("CARGO_HOME", "C:\rust\.cargo", "User")
[Environment]::SetEnvironmentVariable("RUSTUP_HOME", "C:\rust\.rust", "User")
[Environment]::SetEnvironmentVariable("PATH", "C:\rust\.cargo\bin", "User")

Now, open the RUSTUP-INIT.exe and press 1 to Proceed with installation
