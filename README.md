# trackingplan-ios



- [ ] Shared member (singleton I guess), so trackingplan object can be accessed through Trackingplan.shared() anywhere in the app. i.e. for stopping it. PTAL at how NetworkInterceptor itself does it, or mimic how other analytics do it.
- [ ] Batching: when we sent the batch: after reaching xKbs, app goes to background, something else?
- [ ] Trackingplan uses some other dependencies. Join all dependencies in the same package.
- [ ] Improve logging, remove prints.
- [ ] Make sure code is elegant and readable for experienced developers.
- [ ] Add Carthage and swift packages support



- [ ] Make sure installing that after installing tp, everything is not blocking the main thread (or anything!). Try Catch everything. App should not ever be broken by this package. VERY IMPORTANT!
- [ ] Actually publish at cocoapods and add install instructions at the readme. Add example of usage of how to initialize and include.


- [ ] Make sure to test all use cases: endpoint not responding, 404, server error etc.

- [ ] Add support.
- [ ] Find out the swift version that is safe for pods and use that version functions
- [ ] Sampling

