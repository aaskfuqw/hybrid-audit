# hybrid-audit

Independent static-analysis audit of the [Hybrid](https://github.com/limitlessprojects/Go-Hybrid) Go-superset compiler.

Live page: https://aaskfuqw.github.io/hybrid-audit/

Findings, repros and the duplicate-checked calibration map are on the page. Every claim is a minimal program the
checker accepts, plus `go -race` / `go build` evidence, at commit `30206b57`.
