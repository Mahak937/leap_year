 let x = [2024,2025,2022,2032];
        console.log(x.map(year=> (year%4 === 0 && year%100 !== 0) || (year%100 === 0 && year%400 === 0)));
