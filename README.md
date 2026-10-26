[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jacob-rodgers)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/yudjinn)

<a href="https://pulse.yudjinn.dev/dmesg.svg">
  <img src="https://pulse.yudjinn.dev/dmesg.svg" alt="Live dmesg feed: what Jacob is building, listening to, and doing" width="100%" />
</a>

<sub>Live feed, rendered by <a href="https://github.com/yudjinn/github_pulse">github_pulse</a>, a Rust Cloudflare Worker. Click the feed to interact with its links.</sub>

**Upstream:** [litestar](https://github.com/litestar-org/litestar/pulls?q=is%3Apr+author%3Ayudjinn+is%3Amerged) · [bitbake-language-server](https://github.com/Freed-Wu/bitbake-language-server/pull/12) · [wezterm](https://github.com/wezterm/wezterm/pull/3761) · [python-pkcs11](https://github.com/pyauth/python-pkcs11/pull/166) · [oelint-adv](https://github.com/priv-kweihmann/oelint-adv/pull/748)

---

```c
/dts-v1/;

/ {
    model = "Jacob Rodgers";
    compatible = "senior-embedded-engineer", "senior-systems-engineer";
    location = "Helsinki, FI";
    status = "okay";   /* open to EU & US-remote roles */

    experience {
        years = <8>;
        focus = "embedded-linux", "distributed-systems", "technical-leadership";
    };

    embedded-linux {
        build-system = "yocto", "bitbake";
        drivers = "gpio", "spi", "phy";
        ota = "swupdate", "dnf";
        archs = "aarch64", "x86_64";
    };

    languages {
        primary = <&c &cpp &rust &python>;
        also = "bash", "go";
    };

    rust: rust {
        async = "tokio", "axum";
        no-std = "embassy";
        boards = "esp32", "arduino", "rp2350";
    };

    python: python {
        services = "middleware", "telemetry";
        frameworks = "fastapi", "django";
    };

    c: c {
        drivers = "gpio", "spi", "phy", "i2c", "lpm";
    };

    cpp: cpp {
        services = "middleware", "telemetry", "gnss";
    };

    projects {
        timber: timber {
            description = "device tree viewer";
            url = "timber.yudjinn.dev";
        };
    };

    tools {
        dt-viewer = <&timber>;
        editor = "helix";
    };

    keyboard {
        model = "dygma defy";
    };

    gamedev {
        engines = "godot", "gamemaker";
    };

    contact {
        linkedin = "linkedin.com/in/jacob-rodgers";
        ko-fi = "ko-fi.com/yudjinn";
    };
};
```
