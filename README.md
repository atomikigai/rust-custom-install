### Custom install Rust Language Windows

<p>Open windows powershell and set this variables:</p>
<pre>
<code>
[Environment]::SetEnvironmentVariable("CARGO_HOME", "C:\rust\.cargo", "User")
[Environment]::SetEnvironmentVariable("RUSTUP_HOME", "C:\rust\.rust", "User")
[Environment]::SetEnvironmentVariable("PATH", "C:\rust\.cargo\bin", "User")
</code>
</pre>

Now, open the RUSTUP-INIT.exe and press 1 to Proceed with installation
