# beaker-google

Beaker library to use the Google hypervisor

# How to use this wizardry

This is a gem that allows you to use hosts with [google compute](google_compute_engine.md) hypervisor with [Beaker](https://github.com/puppetlabs/beaker).

See the [documentation](docs/manual.md) for the full manual.

### Right Now? (beaker 3.x)

This gem is already included as [beaker dependency](https://github.com/puppetlabs/beaker/blob/master/beaker.gemspec)
for you, so you don't need to do anything special to use this gem's
functionality with Beaker.

### In beaker's Next Major Version? (beaker 4.x)

In Beaker's next major version, the requirement for `beaker-google` will be
pulled from that repo. When that happens, then the usage pattern will change.
In order to use this then, you'll need to include `beaker-google` as a dependency
right next to beaker itself.

# Contributing

Please refer to puppetlabs/beaker's [contributing](https://github.com/puppetlabs/beaker/blob/master/CONTRIBUTING.md) guide.
