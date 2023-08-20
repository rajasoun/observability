# 🚀 Load Testing Observability Stack

Jump right into the world of application monitoring and testing with the Load Testing Observability Stack! This toolkit is your one-stop destination for effortlessly managing and observing applications, featuring the might of Prometheus, Grafana, Loki, Promtail, and k6.

## 🎯 Getting Started:

1. Make sure you've got Docker and Docker Compose ready to roll.
2. Grab the latest version of this repository.
3. Dive into the directory with the `docker-compose.yml` file.
4. Fire up the engines with: `assist.sh start`
5. Once it's up, say hello to Grafana at `http://localhost:3000`. Don't forget the credentials: `admin` for both username and password.

And voila! Dive into a world of metrics, logs, and performance insights. 📊

## 🛠 Script Highlights:

Our knight in shining armor, `assist.sh`, is here to aid you with:

1. **Start Services**: Booting up our entire suite of tools.
2. **Stop Services**: Winding things down when you're done.
3. **Check Service Status**: A peek into how each service is doing.
4. **Run Load Tests with K6**: Unleash the power of K6 testing on your environment.

## 🚦 Quick Commands:

Lost in the sea of options? Here's your lifeboat:

1. 🚀 **Kick Things Off**:
    ```bash
    ./assist.sh start
    ```

2. 🛑 **Wind Things Down**:
    ```bash
    ./assist.sh stop
    ```

3. 🧐 **Service Check-Up**:
    ```bash
    ./assist.sh status
    ```

4. 🎢 **Test the Waters with K6**:
    ```bash
    ./assist.sh load
    ```

5. 🤷 **A Little Guidance**:
    ```bash
    ./assist.sh
    ```

## 🧩 Puzzle Pieces:

Here's a look at the superstars that make this stack rock:

1. **Grafana**: The artist of the group, turning data into stunning visuals.
2. **Prometheus**: The brain, constantly thinking and analyzing every piece of time-series data.
3. **Loki**: The storyteller, aggregating logs and weaving them into a coherent tale.
4. **Promtail**: The scribe, jotting down every event into Loki's grand storybook.
5. **k6**: The adventurer, challenging systems and bringing back tales of performance.

Get ready, strap in, and embark on an exhilarating journey into the world of application monitoring and testing. Happy observing! 🌟🔭📈