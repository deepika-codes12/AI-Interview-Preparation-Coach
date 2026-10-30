# Multimodal Demonstration — Image-Based IT Support Triage

## Input asset
`Multimodal_IT_Support_Sample.png`

This is a synthetic training screenshot created for the capstone. It is clearly labelled as simulated and contains no real user or company data.

## Visual observations
- The visible error reads **“Network path not found.”**
- The affected location is a UNC network path: `\\fileserver\department`.
- The message says Windows cannot access the shared department folder.
- The screenshot does not establish whether the root cause is the client device, DNS/name resolution, network connectivity, server availability, permissions, or an incorrect path.

## AI-assisted interpretation
The image suggests a shared-folder access/connectivity issue. It is not enough evidence to conclude that the file server is down or that the user lacks permission.

## Safe first-response workflow
1. Ask whether other users can access the same share and whether the issue affects one user or many.
2. Confirm the exact path spelling and whether the user is connected to the organisation's network/VPN, if applicable.
3. Check basic connectivity and name resolution using approved support procedures.
4. Check whether the file server/share is reachable and whether there is a known outage.
5. If connectivity is healthy, verify the user's authorised access and group membership through approved procedures.
6. Record the exact error, time, affected user/device, scope and troubleshooting steps in the ticket.
7. Escalate to the network/server team if the issue affects multiple users or requires privileged access.

## Multimodal skill demonstrated
The AI assistant interpreted a visual input, extracted the visible error/path, distinguished observations from possible causes, and produced a cautious troubleshooting plan. This demonstrates image understanding plus reasoning and structured response generation.

## Limitations
- This is a synthetic example, not a real Windows screenshot or a live production incident.
- No actual network diagnostics were run.
- The suggested steps are a training workflow; real organisations may have different tools and escalation rules.
- Do not claim the issue was fixed. The demonstration is triage and interpretation only.

## Live demo
Open the PNG, provide it as an image input to the AI assistant, and ask: “Read this support screenshot. Separate visible facts from possible causes, then give safe first-response troubleshooting steps for an L1 support analyst. Do not assume the server is down.”
