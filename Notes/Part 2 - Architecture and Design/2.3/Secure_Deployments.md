# Secure Deployments

How can we safely and reliably deploy our code from the development environment to production?

**Sandboxing**
- isolated testing environment
    - safe space
    - no connection to prod etc.
use during development process
- incremental application development 
- **Development > QA > Staging > Deployment > Production**

**Secure Baselines**
- security of application should be well defined
- all apps must follow this baseline (e.g. firewall settings , patchs, OS versions etc.)
- baseline should constantly stay up to date
- integrity checks in production
    - ensure security measures matches baseline
    - correct failures asap