**seconds 0:20** from present 11619: 54 presents, frame p50 364.7 / p90 411.5 / p99 451.0 / max 451.0 ms, GPU busy 125.0 ms per present
AMD Radeon RX 9060 XT (RADV GFX1200), radv Mesa 26.3.1-arch3.4, Linux 7.3.5-1-cachyos, 1920x1080, commit 51b5f93df23b, dropped: yes

```json
{"commit":"51b5f93df23b","dirty":false,"env":{"APS5_DUMP_FRAMES":"100000","APS5_DUMP_FRAMES_EVERY":"120","APS5_NO_PAD_INPUT":"1","APS5_NO_UNIT_SHADOW":"1","APS5_PAD_INPUT_FILE":"<path>","APS5_TRACE_DIR":"<path>","APS5_TRACE_SECONDS":"0:20","APS5_TRACE_TRIGGER_FILE":"<path>"},"gpu":"AMD Radeon RX 9060 XT (RADV GFX1200)","driver":"radv Mesa 26.3.1-arch3.4","os":"Linux 7.3.5-1-cachyos","cpu":"AMD Ryzen 9 9900X 12-Core Processor","cpu_threads":24,"memory_mib":31183,"title_id":"PPSA01341","title":"Demon's Souls","content_version":"01.007.000","resolution":"1920x1080","window":{"spec":"seconds 0:20","first_present":11619,"ms":20091.3},"presents":54,"frame_ms":{"p50":364.692,"p90":411.496,"p99":450.995,"max":450.995},"gpu_busy_ms_per_present":125.022,"worker_busy_pct":{"queue worker 0x0":99.328,"queue worker 0x20":70.636,"queue worker 0x30":97.857,"queue worker 0x28":63.051,"queue worker 0x38":95.173,"queue worker 0x48":61.39,"queue worker 0x50":79.438,"queue worker 0x40":67.19},"phase_totals_ms":{"Driver.Completion":6.175,"Driver.Dispatch":12371.246,"Driver.Dispatch.capture_resources":1401.522,"Driver.Dispatch.decode_key_device_setup":1079.576,"Driver.Dispatch.lookup_cache":576.785,"Driver.Dispatch.materialize":171.728,"Driver.Dispatch.prepared_invocation":115.857,"Driver.Draw":9706.407,"Driver.Draw.device_setup":259.372,"Driver.Draw.draw_enqueued":3739.623,"Driver.Draw.empty_indirect_skipped":9.826,"Driver.Draw.post_compile_prepare":50.83,"Driver.Draw.prepare":977.447,"Driver.Draw.shader_compile_and_link":4406.247,"Driver.EndSubmission":553.942,"Driver.Packet":126812.379,"Driver.Packet.device_lock":43.02,"Driver.Packet.dispatch":14035.03,"Driver.Packet.draw":9609.302,"Driver.Packet.execute":174.108,"Driver.Packet.flip_flush":24.146,"Driver.Packet.flush_between_packets":1787.159,"Driver.Packet.memory_wait":100694.003,"Driver.Packet.pipeline_drain":212.479,"Driver.Packet.pipeline_prepare":63.154,"Driver.Packet.prepare_memory":71.735,"Driver.Packet.rendering_wait":0.097,"Driver.Present":73.84,"Driver.Present.acquire_image":6.062,"Driver.Present.device_setup":0.048,"Driver.Present.gpu_mutex_wait":21.451,"Driver.Present.inflight_wait":0.66,"Driver.Present.present_display_buffer":39.058,"Driver.Present.queue_present":1.51,"Driver.Present.release_and_callback":0.039,"Driver.Present.render_fence_wait":4.891,"Driver.Present.resize":0.091,"Driver.Present.validate":0.017,"Driver.Suspend":19.176,"GpuMutex.wait.copy":240.875,"GpuMutex.wait.dispatch":2322.963,"GpuMutex.wait.draw":441.272,"GpuMutex.wait.end":118.314,"GpuMutex.wait.fill":4.404,"GpuMutex.wait.flush":113.022,"GpuMutex.wait.hook":921.019,"GpuMutex.wait.indirect":575.916,"GpuMutex.wait.label":214.926,"GpuMutex.wait.present":21.367,"GpuMutex.wait.wait":37.734,"Graphics.Draw":3688.848,"Graphics.Draw.draw_and_resource_release":2740.903,"Graphics.Draw.index_upload":622.352,"Graphics.Draw.validate":283.128,"Graphics.Draw.vertex_upload":14.055,"Graphics.DrawWithRecipe":70.505,"Graphics.DrawWithRecipe.draw_and_resource_release":67.662,"Graphics.DrawWithRecipe.index_upload":1.183,"Graphics.DrawWithRecipe.validate":0.966,"Graphics.DrawWithRecipe.vertex_upload":0.356,"Recorder.Reap":156.334,"Recorder.Submit":3571.19,"Recorder.WaitSerial":0.28,"Resources.Complete":859.713,"Resources.Prepare":296.967,"Shader.DrawStage":5825.352,"Shader.DrawStage.capture_resources":4502.84,"Shader.DrawStage.materialize":824.311,"Shader.DrawStage.prepared_invocation":449.963,"Shader.ResolveAbi":181.779,"Shader.ResolveGraphicsAbi":64.109,"Shader.ResolveGraphicsStagesAbi":152.425,"VideoOut.Flip":74.42,"VideoOut.Flip.completion_mutex_wait":0.026,"VideoOut.Flip.config_mutex_wait":0.004,"VideoOut.Flip.frame_limit":0.037,"VideoOut.Flip.notify_game":1.004,"VideoOut.Flip.present":72.938,"VideoOut.Flip.validate":0.069,"VideoOut.Flip.vblank_wait":0.061,"VideoOut.Flip.window_prepare":0.101,"VideoOut.Flip.window_title":0.164,"VideoOut.Readiness":0.164,"VideoOut.Readiness.locks_validate":0.09,"Vulkan.Acquire":5.849,"Vulkan.Acquire.acquire_fence_wait":0.094,"Vulkan.Acquire.acquire_image":5.505,"Vulkan.Acquire.fence_reset":0.214,"Vulkan.Acquire.retired_swapchains":0.023,"Vulkan.Dispatch":4393.487,"Vulkan.Dispatch.command_record":2084.994,"Vulkan.Dispatch.shader_resources":2290.248,"Vulkan.DispatchRecipe":5.365,"Vulkan.DispatchRecipe.command_record":5.28,"Vulkan.DrawFromRecipe":71.296,"Vulkan.GraphicsPipeline":0.383,"Vulkan.GraphicsPipeline.create":0.221,"Vulkan.GraphicsPipeline.modules_and_state":0.16,"Vulkan.GraphicsPipelineLibrary":0.08,"Vulkan.GraphicsPipelineLink":0.044,"Vulkan.Present":38.433,"Vulkan.Present.command_record_scale":1.266,"Vulkan.Present.pixel_upload":12.687,"Vulkan.Present.queue_submit":24.439,"Vulkan.QueuePresent":1.443,"Vulkan.QueuePresent.queue_present":1.306,"Vulkan.Retire":4.837,"Vulkan.Retire.dump":0.062,"Vulkan.Retire.wait":4.292},"top_phases_ms_per_frame":{"Driver.Packet":2348.377,"Driver.Packet.memory_wait":1864.704,"Driver.Packet.dispatch":259.908,"Driver.Dispatch":229.097,"Driver.Draw":179.748,"Driver.Packet.draw":177.95,"Shader.DrawStage":107.877,"Shader.DrawStage.capture_resources":83.386},"owned_draw_counts":{},"graphics_track":{"Graphics.Barrier.copy":3676,"Graphics.Barrier.dcc-clear":1080,"Graphics.Barrier.dcc-keys":774,"Graphics.Barrier.dispatch-lead":139811,"Graphics.Barrier.dispatch-trail":127746,"Graphics.Barrier.draw":34268,"Graphics.Barrier.fill":2379,"Graphics.Barrier.fill-clear":216,"Graphics.Barrier.indirect-args":13500,"Graphics.Barrier.label-run":37078,"Graphics.Barrier.present-blit":108,"Graphics.Barrier.staging-in":217328,"Graphics.Barrier.staging-out":107608,"Graphics.Barrier.storage-upload":9372,"Graphics.Barrier.storage-writeback":33683,"Graphics.Barrier.template-refresh":6318,"Graphics.BarrierMerged.copy":2232,"Graphics.BarrierMerged.dispatch-lead":14935,"Graphics.BarrierMerged.fill":421,"Graphics.BarrierMerged.label-run":85,"Graphics.BarrierMerged.staging-in":104802,"Graphics.BarrierMerged.staging-out":107608,"Graphics.BarrierMerged.storage-writeback":5656,"Graphics.Copy":187509,"Graphics.Copy.bytes":87987597160,"Graphics.RenderPass":16147,"Graphics.RenderPass.Close.command":2099,"Graphics.RenderPass.Close.image":10129,"Graphics.RenderPass.Close.key":486,"Graphics.RenderPass.Close.label":85,"Graphics.RenderPass.Close.new-batch":3348,"Graphics.RenderPass.Continued":315178},"trace_dropped":true,"trace_dropped_threads":{"queue worker 0x0":{"events_full_after_s":5.335,"events_lost":720920,"totals_full":false}},"trace":"aps5-trace-51b5f93df23b-603254.json.gz"}
```

**Incomplete trace:** recorded data was lost. Slice-based timings, waits and batch inventories cover retained events only; missing slices are not idle time. Summary statistics are reported separately.
- queue worker 0x0: 720920 events lost; buffer full at 5334.7 ms; over the 14 of 54 frames that ended before it: busy 278.7 ms per frame (75 %), wait 34.4, largest Driver.Packet 312.7, Driver.Suspend 0.3 (the thread table divides the retained slices by every frame)

**Slowest frames** (largest slices inside each, inclusive)

- present 11659: 451.0 ms at 14746 ms: Driver.Packet (queue worker 0x30) 440.9, Driver.Packet.memory_wait (queue worker 0x30) 421.6, Driver.Packet (queue worker 0x38) 388.6, Driver.Packet.memory_wait (queue worker 0x38) 373.0
- present 11623: 441.4 ms at 1441 ms: Driver.Packet (queue worker 0x30) 430.7, Driver.Packet.memory_wait (queue worker 0x30) 405.0, Driver.Packet (queue worker 0x0) 381.9, Driver.Packet (queue worker 0x38) 377.9
- present 11632: 439.4 ms at 4773 ms: Driver.Packet (queue worker 0x30) 425.6, Driver.Packet.memory_wait (queue worker 0x30) 405.8, Driver.Packet (queue worker 0x0) 380.5, Driver.Packet (queue worker 0x38) 360.9
- present 11668: 416.4 ms at 18189 ms: Driver.Packet (queue worker 0x30) 406.1, Driver.Packet.memory_wait (queue worker 0x30) 384.0, Driver.Packet (queue worker 0x38) 350.8, Driver.Packet.memory_wait (queue worker 0x38) 336.9
- present 11660: 415.0 ms at 15197 ms: Driver.Packet (queue worker 0x30) 402.2, Driver.Packet (queue worker 0x38) 401.3, Driver.Packet.memory_wait (queue worker 0x38) 386.3, Driver.Packet.memory_wait (queue worker 0x30) 377.9

**Persistent spikes** (frame time above the fastest frame that separates it from a longer frame; one entry per stall, not per frame)

- present 11659: 451.0 ms at 14746 ms, persistence 117.8 ms
- present 11623: 441.4 ms at 1441 ms, persistence 92.3 ms
- present 11632: 439.4 ms at 4773 ms, persistence 90.1 ms
- present 11668: 416.4 ms at 18189 ms, persistence 58.0 ms
- present 11650: 411.5 ms at 11427 ms, persistence 54.0 ms
- present 11641: 395.0 ms at 8099 ms, persistence 36.7 ms
- present 11619: 368.5 ms at 0 ms, persistence 35.4 ms
- present 11665: 381.8 ms at 17071 ms, persistence 20.3 ms
- present 11672: 381.6 ms at 19710 ms, persistence 19.6 ms
- present 11625: 378.2 ms at 2244 ms, persistence 16.8 ms

**Threads** (ms per frame)

| thread | busy | wait | untraced | in slices < 20 us | largest |
|---|---|---|---|---|---|
| title | 0.0 (0 %) | 0.1 (0 %) | 372.0 | 0.6 | Shader.ResolveAbi 0.0, Shader.ResolveGraphicsAbi 0.0 |
| title | 0.0 (0 %) | 0.1 (0 %) | 371.9 | 0.6 | Shader.ResolveGraphicsAbi 0.0, Shader.ResolveAbi 0.0 |
| title | 0.1 (0 %) | 0.1 (0 %) | 371.9 | 0.8 | Shader.ResolveAbi 0.0, Shader.ResolveGraphicsStagesAbi 0.0 |
| title | 0.1 (0 %) | 0.1 (0 %) | 371.9 | 0.7 | Shader.ResolveAbi 0.0, Shader.ResolveGraphicsAbi 0.0 |
| title | 0.0 (0 %) | 0.0 (0 %) | 372.0 | 0.9 | Shader.ResolveAbi 0.0, Shader.ResolveGraphicsStagesAbi 0.0 |
| title | 0.1 (0 %) | 0.1 (0 %) | 371.9 | 0.6 | Shader.ResolveGraphicsAbi 0.0, Shader.ResolveAbi 0.0 |
| title | 0.1 (0 %) | 0.1 (0 %) | 371.9 | 0.8 | Shader.ResolveGraphicsStagesAbi 0.0, Shader.ResolveAbi 0.0 |
| title | 0.0 (0 %) | 0.1 (0 %) | 372.0 | 0.7 | Shader.ResolveAbi 0.0, Shader.ResolveGraphicsStagesAbi 0.0 |
| title | 0.1 (0 %) | 0.0 (0 %) | 372.0 | 0.5 | Shader.ResolveGraphicsAbi 0.0, Shader.ResolveAbi 0.0 |
| queue worker 0x0 | 73.9 (20 %) | 9.4 (3 %) | 288.7 | 134.7 | Driver.Packet 83.2, Driver.Suspend 0.1 |
| draw committer | 56.2 (15 %) | 11.7 (3 %) | 304.1 | 81.0 | Graphics.Draw 30.5, Recorder.Submit 24.8 |
| presenter | 0.9 (0 %) | 0.5 (0 %) | 370.7 | 0.0 | VideoOut.Flip 1.4, Driver.Present 0.0 |
| title | 0.1 (0 %) | 0.0 (0 %) | 372.0 | 0.6 | Shader.ResolveAbi 0.0, Shader.ResolveGraphicsStagesAbi 0.0 |
| queue worker 0x20 | 9.9 (3 %) | 361.8 (97 %) | 0.4 | 2.6 | Driver.Packet 261.0, Driver.EndSubmission 1.5 |
| queue worker 0x30 | 8.6 (2 %) | 362.9 (98 %) | 0.5 | 1.8 | Driver.Packet 361.3, Driver.EndSubmission 2.4 |
| queue worker 0x28 | 3.7 (1 %) | 368.0 (99 %) | 0.4 | 2.3 | Driver.Packet 232.7, Driver.EndSubmission 1.6 |
| queue worker 0x38 | 8.6 (2 %) | 362.6 (97 %) | 0.9 | 4.1 | Driver.Packet 351.8, Driver.EndSubmission 1.5 |
| queue worker 0x48 | 2.4 (1 %) | 369.5 (99 %) | 0.1 | 0.2 | Driver.Packet 227.2, Driver.EndSubmission 1.1 |
| queue worker 0x50 | 39.9 (11 %) | 329.4 (89 %) | 2.7 | 18.6 | Driver.Packet 292.2, Driver.EndSubmission 1.0 |
| queue worker 0x40 | 4.4 (1 %) | 367.5 (99 %) | 0.2 | 0.5 | Driver.Packet 248.8, Driver.EndSubmission 1.1 |
| gpu | 122.8 (33 %) | 0.0 (0 %) | 249.2 | 0.0 | batch 122.8 |

**Largest slices** (ms per frame, inclusive, all threads): Driver.Packet 2058.2, Driver.Packet.memory_wait 1861.5, Driver.WorkerWait 614.0, Driver.WorkerWait.idle_and_completion_poll 614.0, Driver.Packet.dispatch 141.7, batch 122.8, Driver.Dispatch 109.1, Recorder.Submit 55.5, Vulkan.Dispatch 36.2, Driver.Draw 34.4

**Longest waits**

- Driver.Packet.memory_wait (queue worker 0x28) 273.9 ms at 15338 ms, present 11660
- Driver.Packet.memory_wait (queue worker 0x20) 264.5 ms at 15335 ms, present 11660
- Driver.Packet.memory_wait (queue worker 0x28) 259.2 ms at 14938 ms, present 11659
- Driver.Packet.memory_wait (queue worker 0x20) 250.6 ms at 14934 ms, present 11659
- Driver.Packet.memory_wait (queue worker 0x28) 250.1 ms at 1632 ms, present 11623
- Driver.Packet.memory_wait (queue worker 0x20) 239.9 ms at 1628 ms, present 11623
- Driver.Packet.memory_wait (queue worker 0x28) 239.5 ms at 17213 ms, present 11665
- Driver.Packet.memory_wait (queue worker 0x30) 238.4 ms at 15215 ms, present 11660
- Driver.Packet.memory_wait (queue worker 0x38) 238.2 ms at 15215 ms, present 11660
- Driver.Packet.memory_wait (queue worker 0x28) 236.3 ms at 2385 ms, present 11625

**Largest GPU batches** (GPU ranges inside, and the CPU slices that recorded each, inclusive)

- batch 5201: 15.7 ms at 11562 ms, present 11650: GPU no ranges; recorded by no CPU slices
- batch 1559: 15.7 ms at 3420 ms, present 11628: GPU no ranges; recorded by Driver.Packet (queue worker 0x0) 23.8, Driver.Packet.dispatch (queue worker 0x0) 22.6, Driver.Dispatch (queue worker 0x0) 22.5, Vulkan.Dispatch (queue worker 0x0) 12.7
- batch 8339: 15.6 ms at 18690 ms, present 11669: GPU no ranges; recorded by no CPU slices
- batch 8665: 15.6 ms at 19418 ms, present 11671: GPU no ranges; recorded by no CPU slices
- batch 3366: 15.6 ms at 7466 ms, present 11639: GPU no ranges; recorded by no CPU slices
