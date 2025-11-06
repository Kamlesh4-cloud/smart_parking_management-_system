# Sprint Backlog – Smart Parking Management System

## 🎯 Sprint 3 Overview

| **Sprint Number** | Sprint 3 |
|-------------------|----------|
| **Sprint Goal** | Implement IoT sensor integration and real-time parking availability |
| **Duration** | 2 Weeks (Week 6-7) |
| **Start Date** | 1/10/2025 |
| **End Date** | 28/10/2025 |
| **Total Story Points** | 49 |
| **Team Velocity** | 18.5 points/sprint |

---

## 📋 Selected User Stories

| Story ID | User Story | Priority | Story Points | Status |
|----------|------------|----------|--------------|---------|
| **US-006** | Real-time availability updates | High | 13 | 🔄 In Progress |
| **US-008** | Extend parking duration | Medium | 5 | 🔄 In Progress |
| **US-013** | Vehicle entry/exit detection | High | 13 | 🔄 In Progress |
| **US-014** | License plate recognition (ANPR) | High | 13 | 🔄 In Progress |
| **US-015** | Sensor health monitoring | Medium | 5 | 🔄 In Progress |

---

## 🛠️ Task Breakdown

### US-006: Real-time Availability (13 pts)

| Task | Assigned To | Hours | Status |
|------|-------------|-------|--------|
| Design WebSocket architecture | Lead Dev | 4h | ✅ Done |
| Implement Socket.io server | Backend Dev | 6h | ✅ Done |
| Real-time slot API | Backend Dev | 8h | 🔄 In Progress |
| WebSocket client integration | Frontend Dev | 6h | 🔄 In Progress |
| Real-time map updates | Frontend Dev | 8h | 📋 To Do |
| Redis caching setup | Backend Dev | 4h | 📋 To Do |
| Integration tests | QA Engineer | 5h | 📋 To Do |

**Subtotal:** 41 hours

---

### US-008: Extend Parking Duration (5 pts)

| Task | Assigned To | Hours | Status |
|------|-------------|-------|--------|
| Extension API design | Backend Dev | 3h | ✅ Done |
| Extension logic implementation | Backend Dev | 6h | ✅ Done |
| Extension UI | Frontend Dev | 4h | 🔄 In Progress |
| Payment integration | Backend Dev | 5h | 🔄 In Progress |
| Unit tests | QA Engineer | 3h | 📋 To Do |

**Subtotal:** 21 hours

---

### US-013: Vehicle Entry/Exit Detection (13 pts)

| Task | Assigned To | Hours | Status |
|------|-------------|-------|--------|
| Setup Raspberry Pi sensors | IoT Dev | 6h | ✅ Done |
| Sensor data collection script | IoT Dev | 8h | ✅ Done |
| MQTT broker setup | IoT Dev | 6h | 🔄 In Progress |
| MQTT subscriber service | Backend Dev | 6h | 🔄 In Progress |
| Event processing logic | Backend Dev | 8h | 🔄 In Progress |
| Database slot update | Backend Dev | 4h | 📋 To Do |
| Sensor testing | QA Engineer | 6h | 📋 To Do |

**Subtotal:** 44 hours

---

### US-014: License Plate Recognition (13 pts)

| Task | Assigned To | Hours | Status |
|------|-------------|-------|--------|
| ANPR library research | IoT Dev | 4h | ✅ Done |
| Camera module setup | IoT Dev | 5h | ✅ Done |
| Image capture implementation | IoT Dev | 6h | 🔄 In Progress |
| ANPR processing engine | IoT Dev | 10h | 🔄 In Progress |
| Plate verification API | Backend Dev | 6h | 🔄 In Progress |
| Database matching | Backend Dev | 6h | 📋 To Do |
| Barrier control | IoT Dev | 8h | 📋 To Do |
| ANPR testing | QA Engineer | 8h | 📋 To Do |

**Subtotal:** 53 hours

---

### US-015: Sensor Health Monitoring (5 pts)

| Task | Assigned To | Hours | Status |
|------|-------------|-------|--------|
| Heartbeat mechanism design | IoT Dev | 4h | ✅ Done |
| Health check service | Backend Dev | 5h | 🔄 In Progress |
| Admin dashboard UI | Frontend Dev | 6h | 🔄 In Progress |
| Alert system | Backend Dev | 4h | 📋 To Do |
| Monitoring tests | QA Engineer | 3h | 📋 To Do |

**Subtotal:** 22 hours

---

## 📊 Sprint Progress

| Day | Tasks Done | Hours Burned | Points Done | Blockers |
|-----|------------|--------------|-------------|----------|
| Day 1 | 4 tasks | 19h | 0 | None |
| Day 2 | 5 tasks | 27h | 0 | MQTT config issue |
| Day 3 | 4 tasks | 26h | 0 | None |
| Day 4 | 4 tasks | 25h | 5 | None |
| Day 5 | 4 tasks | 26h | 0 | ANPR tuning |

---

## 🔥 Burn-down Chart
```
Points
50 |●
45 |  ●
40 |    ●___Ideal
35 |      ●
30 |        ●___Actual
25 |          ●
20 |            ●
   |_________________
   Day 1  3  5  7  9
```

---

## 👥 Team Capacity

| Member | Role | Hours/Day | Total (10 days) |
|--------|------|-----------|-----------------|
| Member 1 | Lead Dev | 6h | 60h |
| Member 2 | Backend Dev | 8h | 80h |
| Member 3 | Frontend Dev | 8h | 80h |
| Member 4 | IoT Dev | 8h | 80h |
| Member 5 | QA Engineer | 7h | 70h |

**Total Capacity:** 370 hours  
**Planned:** 181 hours

---

## ⚠️ Risks & Blockers

| Risk | Impact | Mitigation |
|------|--------|------------|
| ANPR accuracy < 90% | High | Manual verification fallback |
| Sensor hardware delay | High | Use simulated data temporarily |
| MQTT instability | Medium | AWS IoT Core backup |

---

## ✅ Definition of Done

- [ ] Code committed to feature branch
- [ ] Unit tests (80%+ coverage)
- [ ] Code review approved
- [ ] Integration tests passing
- [ ] API documentation updated
- [ ] Product Owner approval
- [ ] Merged to develop branch
- [ ] Deployed to staging

---

## 📅 Ceremonies

| Event | When | Duration |
|-------|------|----------|
| Daily Standup | 9:30 AM | 15 min |
| Sprint Review | Day 10, 3:00 PM | 2 hours |
| Retrospective | Day 10, 5:00 PM | 1 hour |

---

**Prepared by:** Scrum Master  
**Status:** In Progress (Day 5/10)  
**Completed:** 5/49 points (10%)  
**Last Updated:** 19/10/2025
