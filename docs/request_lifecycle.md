# Request Lifecycle

## General Carter Request

1. User submits a request through an authenticated interface.
2. Carter validates access and starts an asynchronous job.
3. Carter appends the user-facing request to short-term conversation state when the workflow requires persistence.
4. PGM assembles governed context from the current request, conversation state, long-term memory, and retrieved knowledge.
5. The selected allowed model generates a response.
6. Carter can stream the response and persist the final user-facing output.
7. Selected runs are written to long-term memory and operational logs.

## EAS Request

1. Engineer submits a problem, optional supporting files, and a help mode.
2. EAS selects public-safe guidance packs conceptually aligned to mode and domain.
3. First stage produces a structured computation plan or qualitative plan.
4. The plan is parsed and validated.
5. MCM runs if deterministic computation is required and supported.
6. EDR, governance status, run health, and evidence basis are assembled.
7. Second stage produces the final Engineering Advisory Report.
8. Final report sanitation removes internal payloads and over-disclosure.

## SIS Request

1. Scientist submits required invention-vector fields and optional controls.
2. SIS validates required input and selected model.
3. SIS assembles private generation instructions.
4. Carter executes the job and returns a structured concept output for human review.

## What Is Not Included

This lifecycle omits backend route names, function names, exact prompt formats, job-store details, raw payloads, authentication internals, model-routing internals, and storage paths.
