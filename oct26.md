## Deliverable 

![](deliv444)

## Stretch Goal 1

![](str444)

## Stretch Goal 2

![](str2444)

## Stretch Goal 3

My computer didn't cooperate, but here's the code that should've produced my movie (although I'm not sure, because usually I troubleshoot after producing the endgoal):

    
    ggaze_adm2 <- ggplot(aze_adm2) +
      geom_sf(aes(fill = log(pop19))) +
      scale_fill_gradient2(low = "blue", mid="yellow", high="red", midpoint = 13)

    plot_gg(ggaze_adm2, multicore = TRUE, width = 6, height=2.7, fov = 70)

    render_snapshot(clear = TRUE)

    render_depth(focallength=100,focus=,72)

    render_movie(aze.mp4)

    save(aze_adm1, aze_adm2, file = "aze_adms_RData"
