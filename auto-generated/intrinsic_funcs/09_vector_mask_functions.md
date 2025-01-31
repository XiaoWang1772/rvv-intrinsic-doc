
## Vector Mask Functions:

### [Vector Mask Load/Store Functions](../rvv-intrinsic-api.md#74-vector-unit-stride-operations):

**Prototypes:**
``` C
vbool1_t __riscv_vlm_v_b1 (const uint8_t *base, size_t vl);
vbool2_t __riscv_vlm_v_b2 (const uint8_t *base, size_t vl);
vbool4_t __riscv_vlm_v_b4 (const uint8_t *base, size_t vl);
vbool8_t __riscv_vlm_v_b8 (const uint8_t *base, size_t vl);
vbool16_t __riscv_vlm_v_b16 (const uint8_t *base, size_t vl);
vbool32_t __riscv_vlm_v_b32 (const uint8_t *base, size_t vl);
vbool64_t __riscv_vlm_v_b64 (const uint8_t *base, size_t vl);
void __riscv_vsm_v_b1 (uint8_t *base, vbool1_t value, size_t vl);
void __riscv_vsm_v_b2 (uint8_t *base, vbool2_t value, size_t vl);
void __riscv_vsm_v_b4 (uint8_t *base, vbool4_t value, size_t vl);
void __riscv_vsm_v_b8 (uint8_t *base, vbool8_t value, size_t vl);
void __riscv_vsm_v_b16 (uint8_t *base, vbool16_t value, size_t vl);
void __riscv_vsm_v_b32 (uint8_t *base, vbool32_t value, size_t vl);
void __riscv_vsm_v_b64 (uint8_t *base, vbool64_t value, size_t vl);
```

### [Vector Mask-Register Logical Functions](../rvv-intrinsic-api.md#161-vector-mask-register-logical-operations):

**Prototypes:**
``` C
vbool1_t __riscv_vmand_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t __riscv_vmand_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t __riscv_vmand_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t __riscv_vmand_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t __riscv_vmand_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t __riscv_vmand_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t __riscv_vmand_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t __riscv_vmnand_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t __riscv_vmnand_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t __riscv_vmnand_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t __riscv_vmnand_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t __riscv_vmnand_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t __riscv_vmnand_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t __riscv_vmnand_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t __riscv_vmandn_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t __riscv_vmandn_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t __riscv_vmandn_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t __riscv_vmandn_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t __riscv_vmandn_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t __riscv_vmandn_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t __riscv_vmandn_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t __riscv_vmxor_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t __riscv_vmxor_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t __riscv_vmxor_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t __riscv_vmxor_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t __riscv_vmxor_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t __riscv_vmxor_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t __riscv_vmxor_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t __riscv_vmor_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t __riscv_vmor_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t __riscv_vmor_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t __riscv_vmor_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t __riscv_vmor_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t __riscv_vmor_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t __riscv_vmor_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t __riscv_vmnor_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t __riscv_vmnor_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t __riscv_vmnor_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t __riscv_vmnor_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t __riscv_vmnor_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t __riscv_vmnor_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t __riscv_vmnor_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t __riscv_vmorn_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t __riscv_vmorn_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t __riscv_vmorn_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t __riscv_vmorn_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t __riscv_vmorn_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t __riscv_vmorn_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t __riscv_vmorn_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t __riscv_vmxnor_mm_b1 (vbool1_t op1, vbool1_t op2, size_t vl);
vbool2_t __riscv_vmxnor_mm_b2 (vbool2_t op1, vbool2_t op2, size_t vl);
vbool4_t __riscv_vmxnor_mm_b4 (vbool4_t op1, vbool4_t op2, size_t vl);
vbool8_t __riscv_vmxnor_mm_b8 (vbool8_t op1, vbool8_t op2, size_t vl);
vbool16_t __riscv_vmxnor_mm_b16 (vbool16_t op1, vbool16_t op2, size_t vl);
vbool32_t __riscv_vmxnor_mm_b32 (vbool32_t op1, vbool32_t op2, size_t vl);
vbool64_t __riscv_vmxnor_mm_b64 (vbool64_t op1, vbool64_t op2, size_t vl);
vbool1_t __riscv_vmmv_m_b1 (vbool1_t op1, size_t vl);
vbool2_t __riscv_vmmv_m_b2 (vbool2_t op1, size_t vl);
vbool4_t __riscv_vmmv_m_b4 (vbool4_t op1, size_t vl);
vbool8_t __riscv_vmmv_m_b8 (vbool8_t op1, size_t vl);
vbool16_t __riscv_vmmv_m_b16 (vbool16_t op1, size_t vl);
vbool32_t __riscv_vmmv_m_b32 (vbool32_t op1, size_t vl);
vbool64_t __riscv_vmmv_m_b64 (vbool64_t op1, size_t vl);
vbool1_t __riscv_vmclr_m_b1 (size_t vl);
vbool2_t __riscv_vmclr_m_b2 (size_t vl);
vbool4_t __riscv_vmclr_m_b4 (size_t vl);
vbool8_t __riscv_vmclr_m_b8 (size_t vl);
vbool16_t __riscv_vmclr_m_b16 (size_t vl);
vbool32_t __riscv_vmclr_m_b32 (size_t vl);
vbool64_t __riscv_vmclr_m_b64 (size_t vl);
vbool1_t __riscv_vmset_m_b1 (size_t vl);
vbool2_t __riscv_vmset_m_b2 (size_t vl);
vbool4_t __riscv_vmset_m_b4 (size_t vl);
vbool8_t __riscv_vmset_m_b8 (size_t vl);
vbool16_t __riscv_vmset_m_b16 (size_t vl);
vbool32_t __riscv_vmset_m_b32 (size_t vl);
vbool64_t __riscv_vmset_m_b64 (size_t vl);
vbool1_t __riscv_vmnot_m_b1 (vbool1_t op1, size_t vl);
vbool2_t __riscv_vmnot_m_b2 (vbool2_t op1, size_t vl);
vbool4_t __riscv_vmnot_m_b4 (vbool4_t op1, size_t vl);
vbool8_t __riscv_vmnot_m_b8 (vbool8_t op1, size_t vl);
vbool16_t __riscv_vmnot_m_b16 (vbool16_t op1, size_t vl);
vbool32_t __riscv_vmnot_m_b32 (vbool32_t op1, size_t vl);
vbool64_t __riscv_vmnot_m_b64 (vbool64_t op1, size_t vl);
```

### [Vector count population in mask Functions](../rvv-intrinsic-api.md#162-vector-count-population-in-mask-vcpopm):

**Prototypes:**
``` C
unsigned long __riscv_vcpop_m_b1 (vbool1_t op1, size_t vl);
unsigned long __riscv_vcpop_m_b2 (vbool2_t op1, size_t vl);
unsigned long __riscv_vcpop_m_b4 (vbool4_t op1, size_t vl);
unsigned long __riscv_vcpop_m_b8 (vbool8_t op1, size_t vl);
unsigned long __riscv_vcpop_m_b16 (vbool16_t op1, size_t vl);
unsigned long __riscv_vcpop_m_b32 (vbool32_t op1, size_t vl);
unsigned long __riscv_vcpop_m_b64 (vbool64_t op1, size_t vl);
// masked functions
unsigned long __riscv_vcpop_m_b1_m (vbool1_t mask, vbool1_t op1, size_t vl);
unsigned long __riscv_vcpop_m_b2_m (vbool2_t mask, vbool2_t op1, size_t vl);
unsigned long __riscv_vcpop_m_b4_m (vbool4_t mask, vbool4_t op1, size_t vl);
unsigned long __riscv_vcpop_m_b8_m (vbool8_t mask, vbool8_t op1, size_t vl);
unsigned long __riscv_vcpop_m_b16_m (vbool16_t mask, vbool16_t op1, size_t vl);
unsigned long __riscv_vcpop_m_b32_m (vbool32_t mask, vbool32_t op1, size_t vl);
unsigned long __riscv_vcpop_m_b64_m (vbool64_t mask, vbool64_t op1, size_t vl);
```

### [Find-first-set mask bit Functions](../rvv-intrinsic-api.md#163-vfirst-find-first-set-mask-bit):

**Prototypes:**
``` C
long __riscv_vfirst_m_b1 (vbool1_t op1, size_t vl);
long __riscv_vfirst_m_b2 (vbool2_t op1, size_t vl);
long __riscv_vfirst_m_b4 (vbool4_t op1, size_t vl);
long __riscv_vfirst_m_b8 (vbool8_t op1, size_t vl);
long __riscv_vfirst_m_b16 (vbool16_t op1, size_t vl);
long __riscv_vfirst_m_b32 (vbool32_t op1, size_t vl);
long __riscv_vfirst_m_b64 (vbool64_t op1, size_t vl);
// masked functions
long __riscv_vfirst_m_b1_m (vbool1_t mask, vbool1_t op1, size_t vl);
long __riscv_vfirst_m_b2_m (vbool2_t mask, vbool2_t op1, size_t vl);
long __riscv_vfirst_m_b4_m (vbool4_t mask, vbool4_t op1, size_t vl);
long __riscv_vfirst_m_b8_m (vbool8_t mask, vbool8_t op1, size_t vl);
long __riscv_vfirst_m_b16_m (vbool16_t mask, vbool16_t op1, size_t vl);
long __riscv_vfirst_m_b32_m (vbool32_t mask, vbool32_t op1, size_t vl);
long __riscv_vfirst_m_b64_m (vbool64_t mask, vbool64_t op1, size_t vl);
```

### [Set-before-first mask bit Functions](../rvv-intrinsic-api.md#164-vmsbfm-set-before-first-mask-bit):

**Prototypes:**
``` C
vbool1_t __riscv_vmsbf_m_b1 (vbool1_t op1, size_t vl);
vbool2_t __riscv_vmsbf_m_b2 (vbool2_t op1, size_t vl);
vbool4_t __riscv_vmsbf_m_b4 (vbool4_t op1, size_t vl);
vbool8_t __riscv_vmsbf_m_b8 (vbool8_t op1, size_t vl);
vbool16_t __riscv_vmsbf_m_b16 (vbool16_t op1, size_t vl);
vbool32_t __riscv_vmsbf_m_b32 (vbool32_t op1, size_t vl);
vbool64_t __riscv_vmsbf_m_b64 (vbool64_t op1, size_t vl);
// masked functions
vbool1_t __riscv_vmsbf_m_b1_m (vbool1_t mask, vbool1_t op1, size_t vl);
vbool2_t __riscv_vmsbf_m_b2_m (vbool2_t mask, vbool2_t op1, size_t vl);
vbool4_t __riscv_vmsbf_m_b4_m (vbool4_t mask, vbool4_t op1, size_t vl);
vbool8_t __riscv_vmsbf_m_b8_m (vbool8_t mask, vbool8_t op1, size_t vl);
vbool16_t __riscv_vmsbf_m_b16_m (vbool16_t mask, vbool16_t op1, size_t vl);
vbool32_t __riscv_vmsbf_m_b32_m (vbool32_t mask, vbool32_t op1, size_t vl);
vbool64_t __riscv_vmsbf_m_b64_m (vbool64_t mask, vbool64_t op1, size_t vl);
```

### [Set-including-first mask bit Functions](../rvv-intrinsic-api.md#165-vmsifm-set-including-first-mask-bit):

**Prototypes:**
``` C
vbool1_t __riscv_vmsif_m_b1 (vbool1_t op1, size_t vl);
vbool2_t __riscv_vmsif_m_b2 (vbool2_t op1, size_t vl);
vbool4_t __riscv_vmsif_m_b4 (vbool4_t op1, size_t vl);
vbool8_t __riscv_vmsif_m_b8 (vbool8_t op1, size_t vl);
vbool16_t __riscv_vmsif_m_b16 (vbool16_t op1, size_t vl);
vbool32_t __riscv_vmsif_m_b32 (vbool32_t op1, size_t vl);
vbool64_t __riscv_vmsif_m_b64 (vbool64_t op1, size_t vl);
// masked functions
vbool1_t __riscv_vmsif_m_b1_m (vbool1_t mask, vbool1_t op1, size_t vl);
vbool2_t __riscv_vmsif_m_b2_m (vbool2_t mask, vbool2_t op1, size_t vl);
vbool4_t __riscv_vmsif_m_b4_m (vbool4_t mask, vbool4_t op1, size_t vl);
vbool8_t __riscv_vmsif_m_b8_m (vbool8_t mask, vbool8_t op1, size_t vl);
vbool16_t __riscv_vmsif_m_b16_m (vbool16_t mask, vbool16_t op1, size_t vl);
vbool32_t __riscv_vmsif_m_b32_m (vbool32_t mask, vbool32_t op1, size_t vl);
vbool64_t __riscv_vmsif_m_b64_m (vbool64_t mask, vbool64_t op1, size_t vl);
```

### [Set-only-first mask bit Functions](../rvv-intrinsic-api.md#166-vmsofm-set-only-first-mask-bit):

**Prototypes:**
``` C
vbool1_t __riscv_vmsof_m_b1 (vbool1_t op1, size_t vl);
vbool2_t __riscv_vmsof_m_b2 (vbool2_t op1, size_t vl);
vbool4_t __riscv_vmsof_m_b4 (vbool4_t op1, size_t vl);
vbool8_t __riscv_vmsof_m_b8 (vbool8_t op1, size_t vl);
vbool16_t __riscv_vmsof_m_b16 (vbool16_t op1, size_t vl);
vbool32_t __riscv_vmsof_m_b32 (vbool32_t op1, size_t vl);
vbool64_t __riscv_vmsof_m_b64 (vbool64_t op1, size_t vl);
// masked functions
vbool1_t __riscv_vmsof_m_b1_m (vbool1_t mask, vbool1_t op1, size_t vl);
vbool2_t __riscv_vmsof_m_b2_m (vbool2_t mask, vbool2_t op1, size_t vl);
vbool4_t __riscv_vmsof_m_b4_m (vbool4_t mask, vbool4_t op1, size_t vl);
vbool8_t __riscv_vmsof_m_b8_m (vbool8_t mask, vbool8_t op1, size_t vl);
vbool16_t __riscv_vmsof_m_b16_m (vbool16_t mask, vbool16_t op1, size_t vl);
vbool32_t __riscv_vmsof_m_b32_m (vbool32_t mask, vbool32_t op1, size_t vl);
vbool64_t __riscv_vmsof_m_b64_m (vbool64_t mask, vbool64_t op1, size_t vl);
```

### [Vector Iota Functions](../rvv-intrinsic-api.md#168-vector-iota-operations):

**Prototypes:**
``` C
vuint8mf8_t __riscv_viota_m_u8mf8 (vbool64_t op1, size_t vl);
vuint8mf4_t __riscv_viota_m_u8mf4 (vbool32_t op1, size_t vl);
vuint8mf2_t __riscv_viota_m_u8mf2 (vbool16_t op1, size_t vl);
vuint8m1_t __riscv_viota_m_u8m1 (vbool8_t op1, size_t vl);
vuint8m2_t __riscv_viota_m_u8m2 (vbool4_t op1, size_t vl);
vuint8m4_t __riscv_viota_m_u8m4 (vbool2_t op1, size_t vl);
vuint8m8_t __riscv_viota_m_u8m8 (vbool1_t op1, size_t vl);
vuint16mf4_t __riscv_viota_m_u16mf4 (vbool64_t op1, size_t vl);
vuint16mf2_t __riscv_viota_m_u16mf2 (vbool32_t op1, size_t vl);
vuint16m1_t __riscv_viota_m_u16m1 (vbool16_t op1, size_t vl);
vuint16m2_t __riscv_viota_m_u16m2 (vbool8_t op1, size_t vl);
vuint16m4_t __riscv_viota_m_u16m4 (vbool4_t op1, size_t vl);
vuint16m8_t __riscv_viota_m_u16m8 (vbool2_t op1, size_t vl);
vuint32mf2_t __riscv_viota_m_u32mf2 (vbool64_t op1, size_t vl);
vuint32m1_t __riscv_viota_m_u32m1 (vbool32_t op1, size_t vl);
vuint32m2_t __riscv_viota_m_u32m2 (vbool16_t op1, size_t vl);
vuint32m4_t __riscv_viota_m_u32m4 (vbool8_t op1, size_t vl);
vuint32m8_t __riscv_viota_m_u32m8 (vbool4_t op1, size_t vl);
vuint64m1_t __riscv_viota_m_u64m1 (vbool64_t op1, size_t vl);
vuint64m2_t __riscv_viota_m_u64m2 (vbool32_t op1, size_t vl);
vuint64m4_t __riscv_viota_m_u64m4 (vbool16_t op1, size_t vl);
vuint64m8_t __riscv_viota_m_u64m8 (vbool8_t op1, size_t vl);
// masked functions
vuint8mf8_t __riscv_viota_m_u8mf8_m (vbool64_t mask, vbool64_t op1, size_t vl);
vuint8mf4_t __riscv_viota_m_u8mf4_m (vbool32_t mask, vbool32_t op1, size_t vl);
vuint8mf2_t __riscv_viota_m_u8mf2_m (vbool16_t mask, vbool16_t op1, size_t vl);
vuint8m1_t __riscv_viota_m_u8m1_m (vbool8_t mask, vbool8_t op1, size_t vl);
vuint8m2_t __riscv_viota_m_u8m2_m (vbool4_t mask, vbool4_t op1, size_t vl);
vuint8m4_t __riscv_viota_m_u8m4_m (vbool2_t mask, vbool2_t op1, size_t vl);
vuint8m8_t __riscv_viota_m_u8m8_m (vbool1_t mask, vbool1_t op1, size_t vl);
vuint16mf4_t __riscv_viota_m_u16mf4_m (vbool64_t mask, vbool64_t op1, size_t vl);
vuint16mf2_t __riscv_viota_m_u16mf2_m (vbool32_t mask, vbool32_t op1, size_t vl);
vuint16m1_t __riscv_viota_m_u16m1_m (vbool16_t mask, vbool16_t op1, size_t vl);
vuint16m2_t __riscv_viota_m_u16m2_m (vbool8_t mask, vbool8_t op1, size_t vl);
vuint16m4_t __riscv_viota_m_u16m4_m (vbool4_t mask, vbool4_t op1, size_t vl);
vuint16m8_t __riscv_viota_m_u16m8_m (vbool2_t mask, vbool2_t op1, size_t vl);
vuint32mf2_t __riscv_viota_m_u32mf2_m (vbool64_t mask, vbool64_t op1, size_t vl);
vuint32m1_t __riscv_viota_m_u32m1_m (vbool32_t mask, vbool32_t op1, size_t vl);
vuint32m2_t __riscv_viota_m_u32m2_m (vbool16_t mask, vbool16_t op1, size_t vl);
vuint32m4_t __riscv_viota_m_u32m4_m (vbool8_t mask, vbool8_t op1, size_t vl);
vuint32m8_t __riscv_viota_m_u32m8_m (vbool4_t mask, vbool4_t op1, size_t vl);
vuint64m1_t __riscv_viota_m_u64m1_m (vbool64_t mask, vbool64_t op1, size_t vl);
vuint64m2_t __riscv_viota_m_u64m2_m (vbool32_t mask, vbool32_t op1, size_t vl);
vuint64m4_t __riscv_viota_m_u64m4_m (vbool16_t mask, vbool16_t op1, size_t vl);
vuint64m8_t __riscv_viota_m_u64m8_m (vbool8_t mask, vbool8_t op1, size_t vl);
```

### [Vector Element Index Functions](../rvv-intrinsic-api.md#169-vector-element-index-operations):

**Prototypes:**
``` C
vuint8mf8_t __riscv_vid_v_u8mf8 (size_t vl);
vuint8mf4_t __riscv_vid_v_u8mf4 (size_t vl);
vuint8mf2_t __riscv_vid_v_u8mf2 (size_t vl);
vuint8m1_t __riscv_vid_v_u8m1 (size_t vl);
vuint8m2_t __riscv_vid_v_u8m2 (size_t vl);
vuint8m4_t __riscv_vid_v_u8m4 (size_t vl);
vuint8m8_t __riscv_vid_v_u8m8 (size_t vl);
vuint16mf4_t __riscv_vid_v_u16mf4 (size_t vl);
vuint16mf2_t __riscv_vid_v_u16mf2 (size_t vl);
vuint16m1_t __riscv_vid_v_u16m1 (size_t vl);
vuint16m2_t __riscv_vid_v_u16m2 (size_t vl);
vuint16m4_t __riscv_vid_v_u16m4 (size_t vl);
vuint16m8_t __riscv_vid_v_u16m8 (size_t vl);
vuint32mf2_t __riscv_vid_v_u32mf2 (size_t vl);
vuint32m1_t __riscv_vid_v_u32m1 (size_t vl);
vuint32m2_t __riscv_vid_v_u32m2 (size_t vl);
vuint32m4_t __riscv_vid_v_u32m4 (size_t vl);
vuint32m8_t __riscv_vid_v_u32m8 (size_t vl);
vuint64m1_t __riscv_vid_v_u64m1 (size_t vl);
vuint64m2_t __riscv_vid_v_u64m2 (size_t vl);
vuint64m4_t __riscv_vid_v_u64m4 (size_t vl);
vuint64m8_t __riscv_vid_v_u64m8 (size_t vl);
// masked functions
vuint8mf8_t __riscv_vid_v_u8mf8_m (vbool64_t mask, size_t vl);
vuint8mf4_t __riscv_vid_v_u8mf4_m (vbool32_t mask, size_t vl);
vuint8mf2_t __riscv_vid_v_u8mf2_m (vbool16_t mask, size_t vl);
vuint8m1_t __riscv_vid_v_u8m1_m (vbool8_t mask, size_t vl);
vuint8m2_t __riscv_vid_v_u8m2_m (vbool4_t mask, size_t vl);
vuint8m4_t __riscv_vid_v_u8m4_m (vbool2_t mask, size_t vl);
vuint8m8_t __riscv_vid_v_u8m8_m (vbool1_t mask, size_t vl);
vuint16mf4_t __riscv_vid_v_u16mf4_m (vbool64_t mask, size_t vl);
vuint16mf2_t __riscv_vid_v_u16mf2_m (vbool32_t mask, size_t vl);
vuint16m1_t __riscv_vid_v_u16m1_m (vbool16_t mask, size_t vl);
vuint16m2_t __riscv_vid_v_u16m2_m (vbool8_t mask, size_t vl);
vuint16m4_t __riscv_vid_v_u16m4_m (vbool4_t mask, size_t vl);
vuint16m8_t __riscv_vid_v_u16m8_m (vbool2_t mask, size_t vl);
vuint32mf2_t __riscv_vid_v_u32mf2_m (vbool64_t mask, size_t vl);
vuint32m1_t __riscv_vid_v_u32m1_m (vbool32_t mask, size_t vl);
vuint32m2_t __riscv_vid_v_u32m2_m (vbool16_t mask, size_t vl);
vuint32m4_t __riscv_vid_v_u32m4_m (vbool8_t mask, size_t vl);
vuint32m8_t __riscv_vid_v_u32m8_m (vbool4_t mask, size_t vl);
vuint64m1_t __riscv_vid_v_u64m1_m (vbool64_t mask, size_t vl);
vuint64m2_t __riscv_vid_v_u64m2_m (vbool32_t mask, size_t vl);
vuint64m4_t __riscv_vid_v_u64m4_m (vbool16_t mask, size_t vl);
vuint64m8_t __riscv_vid_v_u64m8_m (vbool8_t mask, size_t vl);
```
