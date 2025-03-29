up/%:
	sudo docker compose -f docker-compose-common.yml -f docker-compose-$*.yml up -d --build

down/%:
	sudo docker compose -f docker-compose-common.yml -f docker-compose-$*.yml down --volumes

#追加
mysql/%:
	sudo docker compose -f docker-compose-common.yml -f docker-compose-$*.yml exec mysql bash

nginx/%:
	sudo docker compose -f docker-compose-common.yml -f docker-compose-$*.yml exec nginx bash