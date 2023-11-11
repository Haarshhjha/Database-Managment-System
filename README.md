# Database-Managment-System
CREATE TABLE amts (
    BusId INT PRIMARY KEY,
    BusNo VARCHAR(50),
    BusCo VARCHAR(30),
    Busroute VARCHAR(40),
    Dtofissue DATE,
    fueltype VARCHAR(20),
    deptsrc VARCHAR(50),
    arrvsrc VARCHAR(50),
    stops INT,
    maintdue DATE
);
INSERT INTO amts(BusId, BusNo, BusCo, Busroute, Dtofissue, fueltype, deptsrc, arrvsrc, stops, maintdue)
VALUES
    (1, 'HJ-01-7373', 'Tata', '79-D', '2020-10-05', 'CNG', 'Godrej Garden City', 'Badrinarayan Society', 66, '2023-08-04'),
    (2, 'HJ-01-3832', 'Tata', '66/3sh-D', '2019-12-04', 'CNG', 'Moti Bhayan Chokdi', 'Sarangpur', 66, '2023-10-24'),
    (3, 'HJ-02-9845', 'Ashok Leyland', '117/1-U', '2021-01-05', 'Petrol', 'Kalupur Terminus', 'Miroli Gam', 55, '2023-12-20'),
    (4, 'HJ-10-1276', 'Tata', '130/2-U', '2022-06-11', 'Diesel', 'Naroda', 'Kamod Gam', 62, '2022-12-24'),
    (5, 'HJ-23-5632', 'Eicher', '135/1-U', '2023-02-28', 'Petrol', 'Lal Darwaja', 'New Ind Colony', 47, '2024-11-09'),
    (6, 'HJ-01-8912', 'Ashok Leyland', '15-U', '2018-04-19', 'Diesel', 'Maninagar', 'Chosar Gam', 44, '2021-07-09'),
    (7, 'HJ-01-7014', 'Eicher', '16-D', '2017-07-01', 'Petrol', 'Someshwar Mahadev', 'Vatva Railway Colony', 99, '2018-08-04'),
    (8, 'HJ-38-0125', 'Tata', '23-U', '2019-09-23', 'Diesel', 'Maninagar', 'Lambha', 40, '2022-07-09'),
    (9, 'HJ-01-6784', 'Eicher', '31-D', '2023-03-26', 'CNG', 'Meghaninagar', 'Sarkhej Gam', 54, '2023-05-10'),
    (10, 'HJ-04-4589', 'Ashok Leyland', '18-D', '2016-10-16', 'Petrol', 'Ujala Circle', 'Nigam Society', 51, '2024-01-08'),
    (11, 'HJ-02-2638', 'Eicher', '22sh-U', '2022-07-02', 'Diesel', 'Lal Darwaja', 'Indiranagar Vibhag-2', 34, '2023-11-25'),
    (12, 'HJ-01-8931', 'Tata', '125/1-U', '2021-06-18', 'CNG', 'Sarangpur', 'Dabhoda', 67, '2022-01-01'),
    (13, 'HJ-01-2365', 'Eicher', '123/1-D', '2023-03-12', 'CNG', 'Parshwanath Township ', 'Sarangpur',22, '2023-08-04'),
    (14, 'HJ-01-5647', 'Ashok Leyland', '20-U', '2017-05-05', 'Diesel', 'Dharmnagar', 'Hatkeshwar Temple', 20, '2018-07-03'),
    (15, 'HJ-01-4328', 'Tata', '67/1sh-D', '2020-09-21', 'Petrol', 'Sattadhar Society', 'Kalupur Terminus', 66, '2023-08-04'),
    (16, 'HJ-01-6731', 'Eicher', '42-U', '2022-10-05', 'CNG', 'Nigam Society', 'Shilaj Gam', 81, '2022-04-04'),
    (17, 'HJ-01-7323', 'Ashok Leyland', '130/4-D', '2019-05-20', 'Diesel', 'Manmohan Park', 'Nava Vadaj', 72, '2021-02-11'),
    (18, 'HJ-01-8902', 'Eicher', '40-D', '2021-07-12', 'Petrol', 'Lapakaman Gam', 'Vaishali Township', 72, '2022-08-01');
