## In short: These are large rhythm game score datasets, free to use.

# Tachi Datasets

[Tachi](https://github.com/zkrising/Tachi) is a rhythm game website that tracks your scores on all your favourite games, and provides *awesome* features like quests, sessions, rivals, and more!

We think it'd be in people's interest to have open, easy-to-use access to the millions of scores and sessions we have on Tachi.

There's no shortage of cool stuff you can do with this data - you could run stats to find out what charts people struggle on, how certain charts have gotten more or less popular over the years...

In short, **you're free to do whatever you want with these large rhythm game datasets**.

I hope it helps you out! I sure wish I had something this practical when I was starting out.

# Recommended Usage

If you are developing stuff for Tachi and need some local data to play with, this is invaluable. **Note that you can log into any users account with `password` as the password!**

If you are a stats nerd, or just a rhythm game nerd in general, this is an excellent resource for doing any sort of analysis. Have fun!

# Usage from Local Tachi

If you have [Tachi](https://github.com/zkrising/Tachi) set up on your local machine, you can use `just load-kamai-dataset` or `just load-boku-dataset`.

# Usage

Download the dump you want from the CDN.

## Kamaitachi

- https://cdn-kamai.tachi.ac/datasets/2024-05.dump

## Bokutachi

- https://cdn-boku.tachi.ac/datasets/2024-05.dump

Install [MongoDB and its CLI Tools](https://www.mongodb.com/try/download/database-tools).

Run `mongorestore --gzip --archive=FILE_NAME_HERE` to restore the database.

You now have a full tachi dataset under `anon-kamai` or `anon-boku` and you can run [MongoDB](https://www.mongodb.com) queries on it.

I highly recommend using [MongoDB Compass](https://www.mongodb.com/products/tools/compass) to play around with your data.

## Anonymisation

This dataset has been anonymised to the best of our ability; no usernames or about me's or anything like that is present.

**All passwords are set to `password`.**

