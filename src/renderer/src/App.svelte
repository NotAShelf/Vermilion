<script lang="ts">
  import Panel from "./components/side/Panel.svelte";
  import View from "./components/view/View.svelte";
  import Miniplayer from "./components/miniplayer/Miniplayer.svelte";
  import Background from "./components/Background.svelte";
    import Notification from "./components/notification/Notification.svelte";
    import GenericPlayer from "./components/drm/GenericPlayer.svelte";
    import TidalDrm from "./components/drm/TidalDRM.svelte";
    import SpotifyPlayer from "./components/drm/SpotifyPlayer.svelte";
</script>

<Background />
<Panel />
<View />
<Miniplayer />
<Notification />

<GenericPlayer/>
<TidalDrm />
<SpotifyPlayer />