int sumSquares(long long k)
{
    int res = 0;
    long long l = ceil(sqrt(k / 2)),r = sqrt(k);
    if (r*r == k) res++;
    for (long i = l; i <= r; i++) {
        long long x = i * i, y = k - x;
        if (y <= 0) continue;
        if (y > x) break;
        long long g = sqrt(y);
        if (g*g == y) 
            res += 1 + (x > y);
    }
    return res;
}
