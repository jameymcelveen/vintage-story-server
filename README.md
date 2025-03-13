docker run --name VintageStory -d \
	-p 42420:42420 \
	--env 'UID=99' \
	--env 'GID=100' \
	--env 'UMASK=000' \
	--env 'DATA_PERM=770' \
	--volume /mnt/cache/appdata/vintagestory:/vintagestory \
	ich777/vintagestory