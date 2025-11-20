# shawking.ca Migration Tracking

Migration of shawking-vars to rhis-builder-inventory/shawking.ca organization

**Started**: 2025-11-19 22:16:50
**Branch**: feature/migrate-shawking-ca
**Status**: In Progress

---

## Phase 0: Backups ✅

**Status**: COMPLETED
**Timestamp**: 2025-11-19 22:16:50

- [x] Create backup of shawking-vars → `shawking-vars.backup-20251119-221650`
- [x] Create backup of rhis-builder-inventory → `rhis-builder-inventory.backup-20251119-221651`

---

## Phase 1: Create shawking.ca Organization Structure

**Status**: IN PROGRESS

### Tasks
- [ ] Copy example.ca → shawking.ca
- [ ] Verify directory structure

### Expected Outcome
Complete shawking.ca directory with all template files from example.ca

---

## Phase 2: Migrate Host Variables

**Status**: PENDING

### Sub-phases
- [ ] 2A: IdM (13 files)
- [ ] 2B: Satellite (55 files + 5 new)
- [ ] 2C: AAP Controller (6 files)
- [ ] 2D: Automation Hub & Provisioner (3 files)

---

## Phase 3: Migrate Group Variables

**Status**: PENDING

### Tasks
- [ ] platform_installer (26 files)
- [ ] provisioner (37 files - rename example.ca → shawking.ca)

---

## Phase 4: Update Inventory Files

**Status**: PENDING

### Tasks
- [ ] Update shawking.ca/inventory/inventory
- [ ] Update workspace inventory file

---

## Phase 5: Global Find and Replace

**Status**: PENDING

### Tasks
- [ ] Replace example.ca → shawking.ca in all files
- [ ] Rename template files

---

## Phase 6: Create Documentation

**Status**: PENDING

### Tasks
- [ ] Create manifests.yml (merged)
- [ ] Create MIGRATION-REPORT.md
- [ ] Create README.md
- [ ] Update .gitignore

---

## Phase 7: Final Verification

**Status**: PENDING

### Tasks
- [ ] Verify file counts
- [ ] Generate summary report
- [ ] Create pull request

---

## Notes

- GitHub Issues disabled on repository - using local tracking
- Using detailed commit messages for traceability
- All phases tracked in this document
