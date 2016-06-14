# Kaper

[![Build Status](https://travis-ci.org/muxinc/kaper.svg?branch=master)](https://travis-ci.org/muxinc/kaper) [![Coverage Status](https://coveralls.io/repos/github/muxinc/kaper/badge.svg?branch=master)](https://coveralls.io/github/muxinc/kaper?branch=master) [![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](http://opensource.org/licenses/MIT)

Elixir client for the [Kapacitor](https://influxdata.com/time-series-platform/kapacitor/) REST API.

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add kaper to your list of dependencies in `mix.exs`:

        def deps do
          [{:kaper, "~> 0.0.1"}]
        end

  2. Ensure kaper is started before your application:

        def application do
          [applications: [:kaper]]
        end

