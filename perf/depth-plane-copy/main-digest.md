**seconds 0:20** from present 15879: 42 presents, frame p50 459.7 / p90 548.3 / p99 830.1 / max 830.1 ms, GPU busy 222.6 ms per present
AMD Radeon RX 9060 XT (RADV GFX1200), radv Mesa 26.3.1-arch3.4, Linux 7.3.5-1-cachyos, 1920x1080, commit 451f25bd2672, dropped: yes

```json
{"commit":"451f25bd2672","dirty":false,"env":{"APS5_DUMP_FRAMES":"100000","APS5_DUMP_FRAMES_EVERY":"120","APS5_NO_PAD_INPUT":"1","APS5_NO_UNIT_SHADOW":"1","APS5_PAD_INPUT_FILE":"<path>","APS5_TRACE_DIR":"<path>","APS5_TRACE_SECONDS":"0:20","APS5_TRACE_TRIGGER_FILE":"<path>"},"gpu":"AMD Radeon RX 9060 XT (RADV GFX1200)","driver":"radv Mesa 26.3.1-arch3.4","os":"Linux 7.3.5-1-cachyos","cpu":"AMD Ryzen 9 9900X 12-Core Processor","cpu_threads":24,"memory_mib":31183,"title_id":"PPSA01341","title":"Demon's Souls","content_version":"01.007.000","resolution":"1920x1080","window":{"spec":"seconds 0:20","first_present":15879,"ms":20291.962},"presents":42,"frame_ms":{"p50":459.746,"p90":548.316,"p99":830.086,"max":830.086},"gpu_busy_ms_per_present":222.575,"worker_busy_pct":{"queue worker 0x0":99.326,"queue worker 0x20":78.022,"queue worker 0x28":70.317,"queue worker 0x30":98.528,"queue worker 0x40":75.841,"queue worker 0x38":93.897,"queue worker 0x50":84.172,"queue worker 0x48":69.253},"phase_totals_ms":{"Driver.Completion":5.446,"Driver.Dispatch":13689.282,"Driver.Dispatch.capture_resources":1125.546,"Driver.Dispatch.decode_key_device_setup":1909.366,"Driver.Dispatch.lookup_cache":448.329,"Driver.Dispatch.materialize":134.679,"Driver.Dispatch.prepared_invocation":93.905,"Driver.Draw":10272.834,"Driver.Draw.device_setup":208.288,"Driver.Draw.draw_enqueued":5524.95,"Driver.Draw.empty_indirect_skipped":7.676,"Driver.Draw.post_compile_prepare":38.48,"Driver.Draw.prepare":760.129,"Driver.Draw.shader_compile_and_link":3504.559,"Driver.EndSubmission":309.461,"Driver.Packet":135505.873,"Driver.Packet.device_lock":33.303,"Driver.Packet.dispatch":17238.925,"Driver.Packet.draw":10181.24,"Driver.Packet.execute":134.914,"Driver.Packet.flip_flush":14.087,"Driver.Packet.flush_between_packets":966.248,"Driver.Packet.memory_wait":106145.603,"Driver.Packet.pipeline_drain":128.735,"Driver.Packet.pipeline_prepare":49.638,"Driver.Packet.prepare_memory":55.02,"Driver.Packet.rendering_wait":0.074,"Driver.Present":37.782,"Driver.Present.acquire_image":2.264,"Driver.Present.device_setup":0.04,"Driver.Present.gpu_mutex_wait":9.436,"Driver.Present.inflight_wait":0.097,"Driver.Present.present_display_buffer":19.885,"Driver.Present.queue_present":1.178,"Driver.Present.release_and_callback":0.029,"Driver.Present.render_fence_wait":4.757,"Driver.Present.resize":0.07,"Driver.Present.validate":0.011,"Driver.Suspend":4.794,"GpuMutex.wait.copy":653.357,"GpuMutex.wait.dispatch":1430.486,"GpuMutex.wait.draw":3393.127,"GpuMutex.wait.end":65.648,"GpuMutex.wait.fill":1.787,"GpuMutex.wait.flush":37.335,"GpuMutex.wait.hook":1107.842,"GpuMutex.wait.indirect":292.581,"GpuMutex.wait.label":106.974,"GpuMutex.wait.present":9.367,"GpuMutex.wait.wait":21.286,"Graphics.Draw":4470.544,"Graphics.Draw.draw_and_resource_release":3728.364,"Graphics.Draw.index_upload":485.534,"Graphics.Draw.validate":223.595,"Graphics.Draw.vertex_upload":11.199,"Graphics.DrawWithRecipe":46.923,"Graphics.DrawWithRecipe.draw_and_resource_release":44.841,"Graphics.DrawWithRecipe.index_upload":0.754,"Graphics.DrawWithRecipe.validate":0.629,"Graphics.DrawWithRecipe.vertex_upload":0.229,"Recorder.Reap":121.26,"Recorder.Submit":2134.32,"Recorder.WaitSerial":0.192,"Resources.Complete":5415.575,"Resources.Prepare":262.341,"Shader.DrawStage":4583.731,"Shader.DrawStage.capture_resources":3505.47,"Shader.DrawStage.materialize":686.048,"Shader.DrawStage.prepared_invocation":352.917,"Shader.ResolveAbi":150.77,"Shader.ResolveGraphicsAbi":47.283,"Shader.ResolveGraphicsStagesAbi":123.472,"VideoOut.Flip":37.608,"VideoOut.Flip.completion_mutex_wait":0.017,"VideoOut.Flip.config_mutex_wait":0.004,"VideoOut.Flip.frame_limit":0.032,"VideoOut.Flip.notify_game":0.491,"VideoOut.Flip.present":36.721,"VideoOut.Flip.validate":0.053,"VideoOut.Flip.vblank_wait":0.042,"VideoOut.Flip.window_prepare":0.075,"VideoOut.Flip.window_title":0.162,"VideoOut.Readiness":0.128,"VideoOut.Readiness.locks_validate":0.074,"Vulkan.Acquire":2.086,"Vulkan.Acquire.acquire_fence_wait":0.072,"Vulkan.Acquire.acquire_image":1.833,"Vulkan.Acquire.fence_reset":0.157,"Vulkan.Acquire.retired_swapchains":0.015,"Vulkan.Dispatch":6048.024,"Vulkan.Dispatch.command_record":1561.717,"Vulkan.Dispatch.shader_resources":4472.945,"Vulkan.DispatchRecipe":4.242,"Vulkan.DispatchRecipe.command_record":4.173,"Vulkan.DrawFromRecipe":47.452,"Vulkan.GraphicsPipeline":0.123,"Vulkan.GraphicsPipeline.create":0.068,"Vulkan.GraphicsPipeline.modules_and_state":0.054,"Vulkan.GraphicsPipelineLibrary":0.025,"Vulkan.GraphicsPipelineLink":0.012,"Vulkan.Present":19.41,"Vulkan.Present.command_record_scale":0.964,"Vulkan.Present.pixel_upload":5.121,"Vulkan.Present.queue_submit":13.293,"Vulkan.QueuePresent":1.126,"Vulkan.QueuePresent.queue_present":1.008,"Vulkan.Retire":4.705,"Vulkan.Retire.wait":4.015},"top_phases_ms_per_frame":{"Driver.Packet":3226.33,"Driver.Packet.memory_wait":2527.276,"Driver.Packet.dispatch":410.451,"Driver.Dispatch":325.935,"Driver.Draw":244.591,"Driver.Packet.draw":242.41,"Vulkan.Dispatch":144.001,"Driver.Draw.draw_enqueued":131.546},"owned_draw_counts":{},"graphics_track":{"Graphics.Barrier.copy":2561,"Graphics.Barrier.dcc-clear":840,"Graphics.Barrier.dcc-keys":548,"Graphics.Barrier.dispatch-lead":108176,"Graphics.Barrier.dispatch-trail":99593,"Graphics.Barrier.draw":28611,"Graphics.Barrier.fill":1820,"Graphics.Barrier.fill-clear":168,"Graphics.Barrier.indirect-args":10500,"Graphics.Barrier.label-run":28859,"Graphics.Barrier.present-blit":84,"Graphics.Barrier.staging-in":168955,"Graphics.Barrier.staging-out":83689,"Graphics.Barrier.storage-upload":7286,"Graphics.Barrier.storage-writeback":26146,"Graphics.Barrier.template-refresh":4654,"Graphics.BarrierMerged.copy":1449,"Graphics.BarrierMerged.dispatch-lead":12417,"Graphics.BarrierMerged.fill":326,"Graphics.BarrierMerged.label-run":1,"Graphics.BarrierMerged.staging-in":81557,"Graphics.BarrierMerged.staging-out":83689,"Graphics.BarrierMerged.storage-writeback":4357,"Graphics.Copy":147612,"Graphics.Copy.bytes":74368029960,"Graphics.RenderPass":12708,"Graphics.RenderPass.Close.command":1831,"Graphics.RenderPass.Close.image":7893,"Graphics.RenderPass.Close.key":345,"Graphics.RenderPass.Close.label":1,"Graphics.RenderPass.Close.new-batch":2638,"Graphics.RenderPass.Continued":244979},"trace_dropped":true,"trace_dropped_threads":{"queue worker 0x0":{"events_full_after_s":7.025,"events_lost":495752,"totals_full":false}},"trace":"aps5-trace-451f25bd2672-592657.json.gz"}
```

**Incomplete trace:** recorded data was lost. Slice-based timings, waits and batch inventories cover retained events only; missing slices are not idle time. Summary statistics are reported separately.
- queue worker 0x0: 495752 events lost; buffer full at 7024.5 ms; over the 14 of 42 frames that ended before it: busy 360.4 ms per frame (76 %), wait 52.9, largest Driver.Packet 412.9, Driver.Suspend 0.2 (the thread table divides the retained slices by every frame)

**Slowest frames** (largest slices inside each, inclusive)

- present 15893: 830.1 ms at 6640 ms: Driver.Packet (queue worker 0x30) 819.2, Driver.Packet.memory_wait (queue worker 0x30) 761.8, Driver.Packet (queue worker 0x50) 749.3, Driver.Packet (queue worker 0x20) 719.4
- present 15911: 805.6 ms at 15315 ms: Driver.Packet (queue worker 0x30) 798.1, Driver.Packet.memory_wait (queue worker 0x30) 734.8, Driver.Packet (queue worker 0x50) 727.5, Driver.Packet (queue worker 0x20) 695.1
- present 15884: 616.7 ms at 2290 ms: Driver.Packet (queue worker 0x30) 609.0, Driver.Packet.memory_wait (queue worker 0x30) 557.6, Driver.Packet (queue worker 0x0) 551.9, Driver.Packet (queue worker 0x50) 538.4
- present 15902: 556.9 ms at 11141 ms: Driver.Packet (queue worker 0x30) 550.6, Driver.Packet.memory_wait (queue worker 0x30) 499.1, Driver.Packet (queue worker 0x38) 485.7, Driver.Packet (queue worker 0x50) 475.0
- present 15920: 548.3 ms at 19744 ms: Driver.Packet (queue worker 0x30) 541.1, Driver.Packet.memory_wait (queue worker 0x30) 489.4, Driver.Packet (queue worker 0x38) 478.3, Driver.Packet (queue worker 0x50) 470.1

**Persistent spikes** (frame time above the fastest frame that separates it from a longer frame; one entry per stall, not per frame)

- present 15893: 830.1 ms at 6640 ms, persistence 414.8 ms
- present 15911: 805.6 ms at 15315 ms, persistence 390.3 ms
- present 15884: 616.7 ms at 2290 ms, persistence 164.2 ms
- present 15902: 556.9 ms at 11141 ms, persistence 121.3 ms
- present 15920: 548.3 ms at 19744 ms, persistence 116.9 ms
- present 15900: 489.0 ms at 10203 ms, persistence 40.5 ms
- present 15906: 469.2 ms at 13047 ms, persistence 31.4 ms
- present 15888: 481.9 ms at 4302 ms, persistence 24.3 ms
- present 15879: 466.0 ms at 0 ms, persistence 12.7 ms
- present 15897: 469.3 ms at 8815 ms, persistence 12.1 ms

**Threads** (ms per frame)

| thread | busy | wait | untraced | in slices < 20 us | largest |
|---|---|---|---|---|---|
| title | 0.1 (0 %) | 0.1 (0 %) | 483.0 | 0.7 | Shader.ResolveAbi 0.1, Shader.ResolveGraphicsStagesAbi 0.0 |
| title | 0.1 (0 %) | 0.1 (0 %) | 482.9 | 1.3 | Shader.ResolveGraphicsStagesAbi 0.1, Shader.ResolveAbi 0.1 |
| title | 0.1 (0 %) | 0.1 (0 %) | 483.0 | 0.7 | Shader.ResolveAbi 0.1, Shader.ResolveGraphicsStagesAbi 0.0 |
| title | 0.1 (0 %) | 0.0 (0 %) | 483.1 | 0.6 | Shader.ResolveAbi 0.1, Shader.ResolveGraphicsStagesAbi 0.0 |
| title | 0.0 (0 %) | 0.1 (0 %) | 483.1 | 0.7 | Shader.ResolveAbi 0.0, Shader.ResolveGraphicsStagesAbi 0.0 |
| title | 0.0 (0 %) | 0.0 (0 %) | 483.1 | 0.6 | Shader.ResolveAbi 0.0, Shader.ResolveGraphicsAbi 0.0 |
| title | 0.0 (0 %) | 0.1 (0 %) | 483.1 | 0.6 | Shader.ResolveAbi 0.0, Shader.ResolveGraphicsAbi 0.0 |
| title | 0.0 (0 %) | 0.0 (0 %) | 483.1 | 0.7 | Shader.ResolveGraphicsAbi 0.0, Shader.ResolveAbi 0.0 |
| title | 0.0 (0 %) | 0.1 (0 %) | 483.1 | 0.6 | Shader.ResolveGraphicsAbi 0.0, Shader.ResolveAbi 0.0 |
| title | 0.0 (0 %) | 0.0 (0 %) | 483.1 | 0.6 | Shader.ResolveAbi 0.0, Shader.ResolveGraphicsStagesAbi 0.0 |
| queue worker 0x0 | 128.5 (27 %) | 18.4 (4 %) | 336.3 | 179.4 | Driver.Packet 146.5, Driver.Suspend 0.1 |
| presenter | 0.6 (0 %) | 0.3 (0 %) | 482.2 | 0.0 | VideoOut.Flip 0.9, Driver.Present 0.0 |
| draw committer | 90.8 (19 %) | 83.1 (17 %) | 309.3 | 78.3 | Graphics.Draw 69.8, Recorder.Submit 20.1 |
| queue worker 0x20 | 23.0 (5 %) | 459.7 (95 %) | 0.5 | 2.6 | Driver.Packet 375.5, Driver.EndSubmission 1.1 |
| queue worker 0x28 | 3.1 (1 %) | 479.5 (99 %) | 0.5 | 2.2 | Driver.Packet 338.3, Driver.EndSubmission 1.1 |
| queue worker 0x30 | 9.8 (2 %) | 472.7 (98 %) | 0.7 | 1.8 | Driver.Packet 473.7, Driver.EndSubmission 1.9 |
| queue worker 0x40 | 5.6 (1 %) | 473.8 (98 %) | 3.8 | 0.5 | Driver.Packet 361.9, Driver.EndSubmission 0.8 |
| queue worker 0x38 | 84.4 (17 %) | 397.9 (82 %) | 0.9 | 4.2 | Driver.Packet 451.7, Driver.EndSubmission 1.1 |
| queue worker 0x50 | 50.1 (10 %) | 430.4 (89 %) | 2.7 | 18.3 | Driver.Packet 403.6, Driver.EndSubmission 0.7 |
| queue worker 0x48 | 13.7 (3 %) | 466.3 (97 %) | 3.2 | 0.2 | Driver.Packet 333.9, Driver.EndSubmission 0.6 |
| gpu | 222.7 (46 %) | 0.0 (0 %) | 260.4 | 0.0 | batch 222.7 |

**Largest slices** (ms per frame, inclusive, all threads): Driver.Packet 2885.1, Driver.Packet.memory_wait 2505.9, Driver.WorkerWait 624.1, Driver.WorkerWait.idle_and_completion_poll 624.1, Driver.Packet.dispatch 295.2, batch 222.7, Driver.Dispatch 208.9, Resources.Complete 127.1, Vulkan.Dispatch 111.6, Vulkan.Dispatch.shader_resources 93.6

**Longest waits**

- Driver.Packet.memory_wait (queue worker 0x28) 417.1 ms at 7052 ms, present 15893
- Driver.Packet.memory_wait (queue worker 0x28) 416.5 ms at 15704 ms, present 15911
- Driver.WorkerWait (queue worker 0x48) 409.7 ms at 6640 ms, present 15893
- Driver.Packet.memory_wait (queue worker 0x20) 400.0 ms at 15701 ms, present 15911
- Driver.Packet.memory_wait (queue worker 0x20) 397.2 ms at 7050 ms, present 15893
- Driver.WorkerWait (queue worker 0x48) 386.1 ms at 15315 ms, present 15910
- Driver.Packet.memory_wait (queue worker 0x28) 367.7 ms at 2539 ms, present 15884
- Driver.Packet.memory_wait (queue worker 0x28) 364.4 ms at 11333 ms, present 15902
- Driver.Packet.memory_wait (queue worker 0x28) 358.6 ms at 19933 ms, present 15920
- Driver.Packet.memory_wait (queue worker 0x28) 357.3 ms at 10335 ms, present 15900

**Largest GPU batches** (GPU ranges inside, and the CPU slices that recorded each, inclusive)

- batch 5493: 25.0 ms at 15494 ms, present 15911: GPU no ranges; recorded by Graphics.Draw (draw committer) 138.3, Graphics.Draw.draw_and_resource_release (draw committer) 138.3, Resources.Complete (draw committer) 137.5, Recorder.Submit (draw committer) 0.5
- batch 5495: 24.4 ms at 15552 ms, present 15911: GPU no ranges; recorded by Recorder.Submit (draw committer) 0.5
- batch 2422: 23.5 ms at 6834 ms, present 15893: GPU no ranges; recorded by Graphics.Draw (draw committer) 170.5, Graphics.Draw.draw_and_resource_release (draw committer) 170.5, Resources.Complete (draw committer) 169.6, Recorder.Submit (draw committer) 0.4
- batch 5491: 22.7 ms at 15390 ms, present 15911: GPU no ranges; recorded by Recorder.Submit (draw committer) 0.5
- batch 5494: 21.7 ms at 15524 ms, present 15911: GPU no ranges; recorded by Recorder.Submit (draw committer) 0.5
