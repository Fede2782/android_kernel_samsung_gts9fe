# SPDX-License-Identifier: GPL-2.0
subdir-y += actions
subdir-y += allwinner
subdir-y += altera
subdir-y += amazon
subdir-y += amd
subdir-y += amlogic
subdir-y += apm
subdir-y += apple
subdir-y += arm
subdir-y += bitmain
subdir-y += broadcom
subdir-y += cavium
subdir-y += exynos
subdir-y += freescale
subdir-y += hisilicon
subdir-y += intel
subdir-y += lg
subdir-y += marvell
subdir-y += mediatek
subdir-y += microchip
subdir-y += nvidia
subdir-y += qcom
subdir-y += realtek
subdir-y += renesas
subdir-y += rockchip
subdir-y += socionext
subdir-y += sprd
subdir-y += synaptics
subdir-y += ti
subdir-y += toshiba
subdir-y += xilinx

dtbo-y += exynos/board/univ/s5e9925-universal9925_rev00.dtbo
dtbo-y += exynos/board/univ/s5e9925-universal9925_rev1b.dtbo
dtbo-y += exynos/board/univ/s5e9925-universal9925_rev17.dtbo
dtbo-y += exynos/board/erd/s5e8535-erd8535.dtbo
dtbo-y += exynos/board/erd/s5e8535-erd8535_r1f.dtbo
dtbo-y += exynos/board/erd/s5e9925-erd9925_r13.dtbo
dtbo-y += exynos/board/erd/s5e9935-erd9935_r01.dtbo
dtbo-y += exynos/board/erd/s5e9935-erd9935.dtbo
dtbo-y += exynos/board/erd/s5e9925-erd9925.dtbo
dtbo-y += exynos/board/erd/s5e8835-erd8835.dtbo
dtb-y += exynos/s5e9925.dtb
dtb-y += exynos/exynos5433-tm2.dtb
dtb-y += exynos/s5e9935.dtb
dtb-y += exynos/exynos5433-tm2e.dtb
dtb-y += exynos/s5e8535.dtb
dtb-y += exynos/exynos7-espresso.dtb
dtb-y += exynos/s5e8835.dtb
dtbo-y += samsung/gts9fe/gts9fe_eur_open_w00_r04.dtbo
dtbo-y += samsung/gts9fe/gts9fe_eur_open_w00_r02.dtbo
dtbo-y += samsung/gts9fe/gts9fe_eur_open_w00_r01.dtbo
dtbo-y += samsung/gts9fe/gts9fe_eur_open_w00_r00.dtbo

targets += dtbs
DTB_LIST  := $(dtb-y) $(dtbo-y)
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
