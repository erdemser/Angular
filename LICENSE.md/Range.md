Range
----------
    TS:
    range = (size: number) => new Array(size).fill(null).map((_, i) => i);
    
    html
    *ngFor="let i of range(1000); trackBy: trackByFn"
