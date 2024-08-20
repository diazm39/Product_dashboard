CREATE TABLE travel_bags (id INTEGER PRIMARY KEY, name TEXT, quantity INTEGER, price INTEGER, color TEXT);

INSERT INTO travel_bags VALUES(1, "fanny pack", 5, 30, "blue");
INSERT INTO travel_bags VALUES(2, "sling bag", 5, 30, "biege");
INSERT INTO travel_bags VALUES(3, "crossbody bag", 5, 30, "grey");
INSERT INTO travel_bags VALUES(4, "tote bag", 5, 60, "black");
INSERT INTO travel_bags VALUES(5, "backpack/sling bag", 5, 80, "black");
INSERT INTO travel_bags VALUES(6, "makeup bag", 5, 30, "black and white");
INSERT INTO travel_bags VALUES(7, "backpack", 4, 80, "grey");
INSERT INTO travel_bags VALUES(8, "passport wallet", 5, 20, "black");
INSERT INTO travel_bags VALUES(9, "carry on bag", 5, 80, "brown");
INSERT INTO travel_bags VALUES(10, "passport covers", 10, 12, "biege");
INSERT INTO travel_bags VALUES(11, "travel pouch", 5, 30, "pink");
INSERT INTO travel_bags VALUES(12, "laptop bag", 4, 40, "grey");
INSERT INTO travel_bags VALUES(13, "laptop case", 4, 20, "grey");
INSERT INTO travel_bags VALUES(14, "toiletries pouch", 5, 20, "grey");
INSERT INTO travel_bags VALUES(15, "duffle bag", 4, 100, "black");
INSERT INTO travel_bags VALUES(16, "snack pouch", 5, 15, "assorted");
INSERT INTO travel_bags VALUES(17, "wallet", 5, 15, "pink");
INSERT INTO travel_bags VALUES(18, "coin purse", 10, 10, "purple");

SELECT * FROM travel_bags;
SELECT * FROM travel_bags WHERE price > 10 ORDER BY price;
SELECT quantity, COUNT(*) FROM travel_bags GROUP BY quantity;
