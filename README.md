# ConvertibleBondsPrice

根據昆明同學描述，可轉債價格為

$CB_t=e^{-r(T-t)}F+qS_tN(d_1)-Fe^{-r(T-t)}N(d_2)$

$d_1=\frac{\ln(\frac{qS_t}{F})+(r+\frac{1}{2}\sigma^2)(T-t)}{\sigma\sqrt{T-t}}$

$d_2=\frac{\ln(\frac{qS_t}{F})+(r-\frac{1}{2}\sigma^2)(T-t)}{\sigma\sqrt{T-t}}=d_1-\sigma\sqrt{T-t}$

其中$CB_t$為可轉債在$t$時間點的價格；$r$為無風險利率；$T$為到期日時機點；$t$為目前時間點；$F$為債券面額；$q$為轉換比率；$\sigma$為股票報酬波動度；$S_t$為股票在$t$的價格。

