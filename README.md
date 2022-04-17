To use this package, just use CustomUnderlineTabIndicator like this:

                     TabBar(
                          isScrollable: true,
                          labelColor: AppColors.textWhite,
                          unselectedLabelColor:
                              AppColors.textWhite.withOpacity(0.4),
                          indicatorColor: AppColors.textWhite,
                          indicatorWeight: 2.0,
                          indicator: const CustomUnderlineTabIndicator(
                            gradient: LinearGradient(
                              colors: [
                                Color(0xff292828),
                                Color(0xff373737),
                                Color(0xff404040),
                                Color(0xffAAAAAA),
                                Color(0xff404040),
                                Color(0xff373737),
                                Color(0xff292828),
                              ],
                            ),
                          ),
                          tabs: const [
                            Tab(
                              text: "Rewards",
                            ),
                            Tab(
                              text: "Offers",
                            ),
                          ],
                        ),
